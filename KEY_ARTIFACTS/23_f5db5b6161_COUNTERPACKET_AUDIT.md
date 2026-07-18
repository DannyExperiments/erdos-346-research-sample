# COUNTERPACKET Audit: Price Construction

Classification: `COUNTERPACKET`

Object: the literal convergence-from-hypotheses formulation of Erdos Problem
346 in `PROBLEM_STATEMENT.md`.

Confidence: high on mathematical correctness and theorem fidelity. The Lean
source was recovered from the public Lean4Web link and contains no `sorry`,
`admit`, custom `axiom`, or `unsafe`. A local kernel replay has not yet been run
on this migrated computer because no Lean toolchain is installed.

Two independent Sol Ultra audits returned `COUNTERPACKET` / `PASS` with no
failed mathematical clause.

## Sources

- `literature/price_counterexample/main.tex`
  - SHA-256: `7605fd52bf4d2d9e73e79ddc286023ec1db75d6f824f676c1b6746d75da607f7`
- `literature/price_counterexample/PriceCounterexample.lean`
  - SHA-256: `5f4c6ec928a08015b90281d5de03d95b97adb4ee0cee2a03b9a5d4254a4f86a6`

The paper constructs a strictly increasing sequence of positive integers for
which finite deletions remain complete, infinite deletions are incomplete,
all consecutive quotients are at least `6/5`, and two quotient subsequences
converge respectively to `phi` and `phi+1/4`.

## Construction

Start with

`a_1=1, a_2=2, a_3=3, a_4=5`,

write `S_n=sum_{r<=n} a_r`, and for `n>=4` impose

`a_{n+1}=S_{n-1}+b_n`, with `0<=b_n<=a_n/4`.

The unperturbed choice is

`p_n=(1-(-1)^n)/2`.

On every long unperturbed stretch, the shifted sequence satisfies Graham's
inhomogeneous Fibonacci recurrence, so every tail of the hypothetical
eventual unperturbed continuation is complete and the relevant ratios tend
to `phi`.

At stage `j`, first continue unperturbed far enough to choose an index `N_j`
such that:

1. each of the first `j` tails has acquired a finite permanent interval
   certificate;
2. `a_{N_j}/a_{N_j-1}` and `S_{N_j-1}/a_{N_j}` are within `1/j` of `phi`.

Then set

`b_{N_j}=floor(a_{N_j}/4)`

and resume the unperturbed rule until the next stage. The certificate is
created before this perturbation is chosen and is permanent under every later
admissible choice.

## Hypothesis 1: Every Finite Deletion Is Complete

The unperturbed recurrence gives every hypothetical eventual unperturbed tail
completeness. From a sufficiently long represented interval in a finite block,
the permanent-certificate lemma propagates an interval with fixed lower
endpoint and unbounded upper endpoint through every later admissible choice.
Stage `j=m` permanently certifies the tail beginning at `a_m`.

Given any finite deleted set, choose `m` beyond its largest index. The complete
tail beginning at `a_m` survives untouched, hence the whole remaining sequence
is complete.

## Hypothesis 2: Every Infinite Deletion Is Incomplete

Let the deleted indices be `i_1<i_2<...`. For sufficiently large `j`, put

`M_j=a_{i_j+1}-1=S_{i_j-1}+b_{i_j}-1`.

All surviving terms with index at least `i_j+1` exceed `M_j`. The sum of all
surviving earlier terms is at most

`S_{i_j-1}-sum_{ell<j} a_{i_ell} <= S_{i_j-1}-3 < M_j`.

Thus `M_j` is not representable after the deletion. Since `M_j` tends to
infinity, the remaining sequence is incomplete.

Paper indexing repair: the displayed recurrence defining `M_j` requires
`i_j>=4`. Replace the paper's `j>=3` by `j>=4` (or simply discard enough
initial deleted indices). This changes no cofinal statement and no hypothesis.
The Lean proof already chooses sufficiently late deleted indices and contains
the corrected boundary.

## Uniform Ratio Gap

Subtracting consecutive defining recurrences gives

`a_{n+1}=a_n+a_{n-1}+b_n-b_{n-1}`

and admissibility gives

`a_{n+1}>=a_n+(3/4)a_{n-1}`.

For all sufficiently late indices the paper derives

`a_{n+1}/a_n>4/3`.

The initial quotients are `2, 3/2, 5/3, 6/5, 2`, so globally

`a_{n+1}/a_n>=6/5`.

## Failure of the Claimed Conclusion

By construction,

`a_{N_j}/a_{N_j-1} -> phi`.

At a perturbation,

`a_{N_j+1}/a_{N_j}`

`=S_{N_j-1}/a_{N_j}+floor(a_{N_j}/4)/a_{N_j}`

`->phi+1/4`.

The quotient sequence therefore has two distinct subsequential limits and
does not converge. This directly refutes the literal statement mounted in
this director run.

## Lean Theorem-Fidelity Audit

The public theorem `Erdos346.erdos346` asserts the existence of a positive
strictly increasing `a : Nat -> Nat` with:

- completeness after every finite set of deleted indices;
- incompleteness after every infinite set of deleted indices;
- the pointwise ratio bound `6/5`;
- the two stated subsequential limits; and
- nonconvergence of the full quotient sequence.

`subsetSums` is defined using a `Finset` of indices, so summands are distinct.
Strict monotonicity makes deletion by index equivalent to deletion by sequence
value. No hypothesis of the original literal statement is weakened.

## Interpretation Boundary

This counterpacket resolves the formulation in which the hypotheses are
supposed to force convergence. It does not refute the different formulation
that assumes the quotient limit exists and asks only for its value. That
limit-exists variant has a separate recent formal proof claiming that the
value must be `phi`.
