# Current Progress Context for V107B - Erdos 346 - 20260628T074307Z

Proof status: #346 is not solved. No counterpacket is banked. No positive Lemma B witness is banked.

Latest clean Fable result: V107A completed as `EXACT_NEW_WALL` from run:

`$USER_HOME/packy-fable-ui/projects/346/runs/2026-06-28T07-35-40-338Z-retry-v107a-wallbreaker-boundary-attack-artifact-stream-auth-3fe52057`

Clean response preserved at:

`V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V107A_BCOMP_THRESHOLD_DICHOTOMY_EXACT_NEW_WALL_20260628T074307Z.md`

Acceptance artifact:

`V105_SOURCE_ARTIFACTS/acceptance_artifacts/v107a_bcomp_threshold_dichotomy_exact_new_wall_acceptance_20260628T074307Z.json`

## V107A Conservative Audit

V107A sharpened the broad V107 import-only wall into a threshold-position dichotomy. It did not solve the problem.

Banked source-valid point:

- `MOUNTED_COMPLETENESS_MONOTONICITY_IS_SUFFIX_SCOPED_V107A`: the mounted V43 monotonicity/completeness transfer is for suffix passage `Tail_m subset Tail_i`; it does not apply to interior deletion `C -> C\S`.

Conditional points only:

- `ABOVE_THRESHOLD_CORE_HOLE_IS_RESIDUAL_EXTERNAL_ESSENTIAL_CONDITIONAL_ON_BSUB_V107A`: if `BSUB` proves `B=C\S subset Tail_i`, then all-tail completeness of `Tail_i` puts any above-threshold core-sum hole for `B` into `FS(Tail_i) \ FS(B)`.
- `V107_TWO_SIDED_IMPORT_FACTORS_THROUGH_BCOMP_ABOVE_THRESHOLD_CONDITIONAL_V107A`: if `BSUB` holds and the hole is above threshold, the proof-side import reduces to deletion-robust block completeness `BCOMP`.

Do not bank either conditional point without verifying its condition.

## Current Live Wall

`V107B_DECIDE_BCOMP_DELETION_ROBUST_BLOCK_COMPLETENESS_FS_C_MINUS_S_SUPSETEQ_THRESHOLD_INTERVAL_FOR_THE_INDUCED_TYPE_I_BLOCK_OR_PROVE_THE_CORE_HOLE_IS_EVENTUALLY_BELOW_THRESHOLD_VIA_THE_THRESHOLD_POSITION_CHECKER_PLUS_VERIFY_BSUB_AS_A_SOURCE_LAW_V1`

First failed clause:

`THE_MOUNTED_SOURCE_PROVES_COMPLETENESS_AND_THRESHOLD_MONOTONICITY_ONLY_UNDER_SUFFIX_PASSAGE_TAIL_M_SUBSET_TAIL_I_GIVING_R_M_GE_R_I_AND_HAS_NO_DELETION_ROBUST_BLOCK_COMPLETENESS_BCOMP_FOR_THE_INTERIOR_CORE_DELETED_RESIDUAL_BLOCK_B_EQUALS_C_MINUS_S_SO_WHILE_H1_PLUS_BSUB_FORCES_EVERY_ABOVE_THRESHOLD_CORE_SUM_HOLE_INTO_FS_TAIL_I_MINUS_FS_B_AS_RESIDUAL_EXTERNAL_ESSENTIAL_IT_CANNOT_BE_UPGRADED_TO_A_CONTRADICTION_WITHOUT_BCOMP_AND_BELOW_THRESHOLD_HOLES_REMAIN_V105Z_V106_IMPORT_ONLY`

## V107B Target

Decide the smallest remaining bridge:

1. Verify `BSUB`: prove from mounted source that the residual block `B=C\S` is a subset of the relevant `Tail_i`. If this is false or unmounted, return the exact missing source-law wall.
2. Decide `BCOMP`: prove, refute, or wall the deletion-robust block completeness claim that `FS(C\S)` covers the required threshold/core-sum interval for the induced Type I block.
3. Run the threshold-position dichotomy: either above-threshold cases reduce to `BCOMP`, holes are eventually below threshold, or the exact split itself is the next wall.

Forbidden moves: no raw materialization, no finite tail grinding, no `pGAP/NUGAP/VALGAP` resurrection, no bounded-block all-tail-completeness misuse, no interior-deletion monotonicity inferred from V43 suffix monotonicity.
