CLASSIFICATION: AUDIT

OBJECT: `V109R1_ROLE7_TYPE_I_SPLICE_CLOSES_ONLY_THE_ABOVE_THRESHOLD_TYPE_I_BRANCH_NOT_FULL_ERDOS_346_V1`

CONFIDENCE: High on the local splice and surviving Type S obstruction; moderate on the full upstream reduction because decisive V19-V42 material and part of V43 are absent.

SOURCE_FILES_READ: All required core files, normalized definitions, V43/V44/V45, V105H/V105N/V105Z/V106/V107A, V107B prompt, acceptance artifact, provenance, manifest, and packet prompt. Every `SHA256SUMS.txt` entry verified. Internet was not used; no files were modified.

**Executive Verdict**
No. As represented in the packet, proving `BSUB + BCOMP_window + non-eventual-below-threshold` does **not yet imply**
\[
\lim_{n\to\infty}\frac{a_{n+1}}{a_n}=\phi.
\]

Those statements close the above-threshold **Type I** branch, provided their quantifiers align. V43’s canonical reduction still permits two Type S infinite-subsequence branches, and V44 explicitly says they are not contradicted. The result is logically
\[
S_{\rm terminal}\lor S_{\rm passive}\lor I,\qquad \neg I,
\]
which leaves \(S_{\rm terminal}\lor S_{\rm passive}\), not a contradiction.

**Local Splice**
For a Type I block \(j\), the source gives
\[
z_j+r\notin FS(B_j)\quad(0\ne r\in FS(I_j))
\]
([V43:419]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:419), [V43:433]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:433), [V43:436]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:436)).

Define
\[
H_{\ge,j}=\{z_j+r:0\ne r\in FS(I_j),\ z_j+r\ge R_{i_j}\}.
\]
Equality belongs here, not in a third branch ([definitions:55]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/NORMALIZED_DEFINITIONS.md:55), [definitions:63]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/NORMALIZED_DEFINITIONS.md:63), [definitions:65]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/NORMALIZED_DEFINITIONS.md:65)).

Thus the Type I profile gives
\[
H_{\ge,j}\cap FS(B_j)=\varnothing.
\]
But `BCOMP_window` is exactly
\[
H_{\ge,j}\subseteq FS(B_j)
\]
([definitions:72]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/NORMALIZED_DEFINITIONS.md:72), [definitions:76]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/NORMALIZED_DEFINITIONS.md:76)). Hence
\[
BCOMP_j\Longrightarrow H_{\ge,j}=\varnothing.
\]

Therefore, if `BCOMP_window` holds for every relevant Type I block while
\[
\forall N\ \exists j\ge N:\ H_{\ge,j}\ne\varnothing,
\]
the Type I cascade is impossible.

**Sharper Delta**
`BSUB` is logically redundant in this final contradiction. Once `BCOMP_window` is assumed, the contradiction is already
\[
H_{\ge,j}\subseteq FS(B_j)
\quad\text{and}\quad
H_{\ge,j}\cap FS(B_j)=\varnothing.
\]
`BSUB` is needed only for V107A’s intermediate conclusion \(H_{\ge,j}\subset FS(Tail_{i_j})\), making the holes residual-external-essential ([V107A:37]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V107A_RESPONSE.md:37), [V107A:41]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V107A_RESPONSE.md:41)).

**Type S Obstruction**
V43 states that every surviving cascade has an infinite subsequence satisfying at least one of three profiles ([V43:354]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:354)):

1. Type S terminal-blocked ([V43:358]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:358)).
2. Type S passive-spectrum ([V43:408]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:408)).
3. Type I transversal-core ([V43:419]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:419)).

The terminal Type S hole is \(R_i-1\), intrinsically below threshold, so `BCOMP_window` does not touch it. V44 says directly that Type S terminal blocking is not contradicted and Type S passive-spectrum remains live ([V44:14]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V44_RESPONSE.md:14), [V44:464]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V44_RESPONSE.md:464), [V44:468]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V44_RESPONSE.md:468)).

This is an implication-graph obstruction, not a local finite-sums countermodel and not an original #346 counterexample.

**Exact Closing Theorem**
A sufficient theorem is:

`FULL_346_CASCADE_CLOSURE_THEOREM`

For every sequence \(A\) satisfying the three original hypotheses and failing the full conclusion \(C(A)\):

1. Choose \(\lambda_A=1+\min(\varepsilon_A/2,1/16)\). Then \(1<\lambda_A<9/8\) and the \(\lambda_A\)-ratio gap follows directly from the original \(\varepsilon_A\)-gap.
2. The full failure \(\neg C(A)\), including nonexistence of the ratio limit, produces a source-valid surviving cascade obeying the exhaustive V43 trichotomy.
3. Neither Type S terminal-blocked nor Type S passive-spectrum can occur on an infinite subsequence.
4. Consequently there is an infinite Type I subsequence \(J_I\).
5. For every \(j\in J_I\), `BCOMP_window_j` holds.
6. On the same \(J_I\),
   \[
   \forall N\ \exists j\in J_I,\ j\ge N:\ H_{\ge,j}\ne\varnothing.
   \]

Clauses 5 and the Type I hole law force \(H_{\ge,j}=\varnothing\) for every \(j\); clause 6 contradicts this. Hence no \(\neg C(A)\) exists, proving the full limit.

Clauses 2-3 may equivalently be replaced by one global selector:
\[
\neg C(A)\Longrightarrow\text{an infinite Type I subsequence satisfying clause 6}.
\]

**Unverified Dependencies**
- `BSUB`: explicitly unverified in the acceptance artifact ([acceptance:23]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V107A_ACCEPTANCE.json:23)).
- `BCOMP_window`: not banked ([acceptance:22]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V107A_ACCEPTANCE.json:22)).
- Threshold cofinality: V107A supplies only a per-block checker specification, explicitly not a theorem ([V107A:45]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V107A_RESPONSE.md:45)).
- Type S closure or an exhaustive Type I selector: absent.
- Full-failure extraction: V106 asserts that a counterpacket induces Type I data ([V106:31]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V106_RESPONSE.md:31)), but the packet does not supply the V19-V42 derivation, and V43 itself is missing original lines 441-623 ([V43:7]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V43_RECOVERED_CANONICAL_EXCERPTS.md:7)).
- Limit-existence coverage: no separate analytic branch is needed if clause 2 starts from the full negation \(\neg(\lim q_n=\phi)\). The packet declares that convention but does not prove the extraction for oscillatory/nonconvergent ratios.
- Lambda uniformity: not required. One sequence-dependent \(\lambda_A\) suffices. What remains unverified is that the entire cascade reduction applies to that chosen \(\lambda_A\); no uniform control as \(\lambda\to1^+\) is needed.
- V44 also expressly disclaims closure of H-Shadow, H-Early, and Branch L ([V44:448]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V44_RESPONSE.md:448), [V44:450]($USER_HOME/ERDOS346_DOL_ULTRA_V109R1_SOURCE_COMPLETE_PACKET_20260712/SOURCE/THEOREM_ARTIFACTS/V44_RESPONSE.md:450)); their definitions and relation to the full counterexample reduction are not supplied.

**First Failed Clause**
`NO_MOUNTED_THEOREM_UPGRADES_THE_V43_TYPE_S_TERMINAL_OR_TYPE_S_PASSIVE_OR_TYPE_I_INFINITE_SUBSEQUENCE_ALTERNATIVE_TO_A_COFINAL_TYPE_I_SUBSEQUENCE_OR_SEPARATELY_RULES_OUT_BOTH_TYPE_S_BRANCHES_FOR_EVERY_ORIGINAL_SEQUENCE_WITH_NOT_LIMIT_RATIO_EQUAL_PHI; THEREFORE_BCOMP_WINDOW_PLUS_NON_EVENTUAL_BELOW_THRESHOLD_PROVES_ONLY_TYPE_I_BRANCH_IMPOSSIBILITY_AND_NOT_FULL_ERDOS_346.`

DO NOT BANK: a proof of #346, a Type S contradiction, an original counterpacket, exhaustive counterexample-to-Type-I extraction, or any theorem from failed V107B/malformed V108/V109 prose.



