# Director State

Director id: `346-director-20260715-v109r1-wave1`

Status: `COUNTERPACKET` banked for the literal convergence-from-hypotheses
formulation mounted in this run. The statement is false.

## Resolution

The Price construction preserved in
`literature/price_counterexample/main.tex` gives a positive strictly increasing
sequence satisfying both deletion hypotheses and

`a_{n+1}/a_n >= 6/5`

for every `n`, while its quotients have subsequences tending to `phi` and
`phi+1/4`. Therefore the quotients do not converge and the literal conclusion
fails.

The exact formal statement is `Erdos346.erdos346` in
`literature/price_counterexample/PriceCounterexample.lean`. Its quantifiers
match H1, H2, H3, and nonconvergence. The recovered file has no `sorry`,
`admit`, custom `axiom`, or `unsafe`. A fresh local kernel replay remains an
operational verification task because this migrated computer has no Lean
toolchain installed; it is not a mathematical gap in the packet.

The full director audit is `COUNTERPACKET_AUDIT.md`.

## Interpretation Boundary

This resolves the formulation in `PROBLEM_STATEMENT.md`, where H1+H2+H3 are
supposed to force existence and value of the quotient limit. It does not refute
the distinct limit-exists formulation, which adds convergence as a hypothesis
and asks only whether the existing limit equals `phi`.

## Superseded Positive-Proof Targets

Before the counterpacket was recovered, the primary target was global
representation-transversal growth. For each sufficiently large represented
integer `n`, `tau_A(n)` denoted the minimum size of a subset of `A` meeting
every distinct-term representation of `n`.

Prove either:

1. every all-tail-complete uniformly ratio-gapped sequence failing convergence
   to `phi` has `tau_A(n)->infinity`, which contradicts infinite-deletion
   minimality by the banked sparse-deletion lemma; or
2. the bounded moving transversals forced along an unbounded target sequence
   imply an asymptotic Fibonacci recurrence and hence ratio convergence to
   `phi`.

The secondary Type I target was:

For the induced Type I blocks produced by a hypothetical non-phi
counterexample, prove that for some sufficiently late block there is
`0!=r in FS(I)` such that

`z0+r >= R_i` and `z0+r in FS(C\S)`.

The banked core-hole says `z0+r notin FS(C\S)` for every such nonzero `r`, so
this fused target closes the current branch immediately.

## Decomposition

- `BSUB`: `B=C\S subset Tail_i`.
- `BCOMP_window`: every above-threshold core candidate is in `FS(C\S)`.
- `THRESHOLD_CROSSING`: a hypothetical cascade has a sufficiently late block
  with a nonempty above-threshold window, or the eventual below-threshold case
  contradicts one of the original deletion hypotheses.

## Local Director Lens

Try to apply completeness to `A\(finite prefix union S)`, control its new
threshold at the moving block scale, and trap a representation inside `C\S`.
If threshold trapping fails, try to diagonalize persistent below-threshold
blocks into an infinite deletion whose complement remains complete.

## Local Bankable Delta

`FINITE_DELETION_LOW_ELEMENT_CAPTURE` is proved in `LOCAL_DIRECTOR_ATTACK.md`.
For `D_i=(A\Tail_i) union S`, a candidate `w` is forced into `FS(C\S)` if
`w` exceeds the completeness threshold of `Tail_i\S` and `C` captures every
undeleted tail element at most `w`. The live BCOMP wall is therefore sharpened
to `POST_DELETE_THRESHOLD_SYNC + LOW_ELEMENT_CAPTURE`, or an explicit repair
map avoiding `S`.

## Wave 1 Integrated Deltas

- BSUB is not needed to infer `H_ge subset FS(Tail_i)\FS(B)` or to combine
  BCOMP with the core-hole. It remains source-undecided and is relevant only
  when a proof needs to place `B` inside a finite-deletion remainder.
- If the finite-deletion embedding is valid, write `rho_{i,S}` for the
  conductor of `Tail_i\S` and `q_{i,B}` for its first surviving element
  outside `B`. Then `[rho_{i,S},q_{i,B}) subset FS(B)`.
- Therefore each Type I hole must escape left or right:
  `w<rho_{i,S} or w>=q_{i,B}`. The new exact hard wall is to rule out both
  escapes on a sufficiently late induced block.
- Mounted representation-repair laws do not bypass this wall. A repair keeping
  the already-good support exists exactly when the defect sum is representable
  in the unused part of `B`; no banked law forces that condition.
- Full-proof audit correction: closing Type I is not yet a packet-complete proof
  of 346. V43 still lists Type S terminal-blocked and Type S passive-spectrum
  alternatives. We need either their separate elimination or a recovered,
  audited theorem sending every original non-phi counterpacket to a cofinal
  Type I subsequence.
- Threshold crossing has the exact normal form
  `R_i-z0 <= sum(I)`. No mounted scale anchor proves this cofinally; the
  opposite regime is `R_i-z0-sum(I)>=1` eventually. Any next threshold attack
  must couple a conductor upper bound to core mass at the same tail index.
- `GLOBAL_TRANSVERSAL_SPARSE_DELETION_DICHOTOMY` is banked. If
  `tau_A(n)->infinity`, choose a sufficiently sparse infinite deletion `D` so
  that `|D cap [1,n]|<tau_A(n)` for every large `n`; then `A\D` remains
  complete, contradicting hypothesis 2.
- Consequently a hypothetical counterexample has `tau_A(n_j)<=K` for some
  unbounded `n_j`. After deleting one fixed finite delta-system root, it has
  pairwise-disjoint nonempty moving transversals `P_j`, each of size at most
  `K`, for the global representation families of `n_j`.
- This global invariant is not the previously cut residual-block invariant
  `tau_B`; it is quantified directly by the original infinite-deletion
  hypothesis and bypasses the forward-only Type I realization wall.

## Source Recovery Correction

The migrated full 346 archive is present at
`$USER_HOME/Library/Mobile Documents/com~apple~CloudDocs/Documents/erdos-research/problems/0346`.
It contains the full V43 response and the V46-V105 continuation omitted from
the V109R1 packet. The Type S warning remains mathematically relevant, but it
is no longer correct to say the source is unavailable. A fresh packet must use
this archive plus the later V105H/V105N/V105Z/V106/V107A artifacts from the
V109R1 packet.

## Wave 2 Route Correction

`GLOBAL_TOP_BAND_TRANSVERSAL_AND_MATCHING_CAP_V1` cuts the primary global
transversal-growth route. If `q=1+epsilon` and
`c=(q-1)/q`, every representation of `n` contains a largest summand in
`A cap (cn,n]`. Lacunarity bounds the size of this top band by a constant
depending only on `epsilon`. Thus both the global transversal number and the
maximum number of pairwise-disjoint representations are uniformly bounded.
In particular, `tau_A(n)->infinity` is impossible under H3, and bounded moving
global transversals alone cannot force Fibonacci asymptotics.

This route cut explains the failure of the immediately preceding positive
proof strategy but is no longer a solve blocker because the literal statement
is refuted by the banked counterpacket.

## Formalization Status

`LEAN_LIVE` for the counterpacket. The public Lean theorem mirrors all literal
problem hypotheses and proves two distinct quotient subsequential limits. The
earlier positive-proof splice remains incomplete and is retained only as
historical work relevant to the separate limit-exists interpretation.
