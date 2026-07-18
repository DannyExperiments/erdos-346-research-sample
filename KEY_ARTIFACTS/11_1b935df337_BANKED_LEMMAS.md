# Banked Lemmas - V102 through V105D Snapshot

Use these as banked route facts, not as a completed proof.

## V105D

`V105D_SIGMA_RIGIDITY_AND_DISCRETE_SEPARATION_INTERVAL_REDUCTION_V1`

- Fixed low-lambda regime remains `1 < lambda < 9/8`; independent Boolean Omega branch data are finite fixed-lambda skeletons.
- With `h > max(E)` and `x = 3^{-h}`, within-shell tail order is rigid and independent of `h`; a `sigma` is valid for every allowed terminal depth or invalid for every allowed terminal depth.
- Valid adjacent lambda-separation inequalities reduce to exact one-variable forms `Delta_i + beta_i*3^{-h} >= 0`, with `beta_i in {-1,0,lambda-1,lambda}`.
- Feasible terminal depths form an exact integer interval `J_S=[H_-,H_+] cap Z`, with `H_+=infinity` allowed. Empty intervals are certified by named `LAMBDA_SEPARATION_FAILURE` data.
- On nonempty intervals, every banked affine sign form `A+B*3^{-h}` is decided by endpoint/single-breakpoint checking.

## V105C

`V105C_NONTERMINAL_DEPTH_CANONICAL_ORDER_AND_TERMINAL_AFFINE_DECISION_REDUCTION_V1`

- Low-lambda exact Omega table reduced to canonical terminal-depth/order decisions and terminal affine sign questions.

## V105B

`V105B_FIXED_OMEGA_POSITIVE_IMAGE_LOG_CAP_AND_SIGN_DECISION_ROUTE_REDUCTION_V1`

- Fixed-lambda Omega images have a log cap and route to sign-decision data; this is not a proof by itself.

## V105A / V105

- Fixed-lambda Boolean/Omega skeleton caps are finite for fixed lambda but nonuniform as lambda -> 1+.
- Stratified base-gap/Boolean alternatives remain route reductions, not contradictions by themselves.

## V104B

`V104B_LAMBDA_STRATIFIED_ACTUAL_EXIT_AND_BOOLEAN_ATOM_PROFILE_REDUCTION_V1`

- High-lambda actual exits collapse to adjacent base-gap profiles.
- Mid-lambda actual exits reduce to base/rank-one singleton profiles.
- Low-lambda branch remains exact fixed-lambda Omega packing.

## V102/V103

- V102/V103 bank the actual-exit/full Boolean-weight packing and Boolean atom cap machinery.
- They explicitly do not prove #346 alone.

## V105E - 20260616T035923Z

`V105E_SEPARATION_SURVIVOR_WEIGHT_COMPARISON_EXHAUSTION_AND_MISSING_REALIZATION_BRIDGE_WALL_V1`

- `WEIGHT_COMPARISON_NONCLOSURE_ON_V105D_SURVIVORS_V105E`: pure order/lambda-separation/K=2/full-weight-packing/cost-cap data do not provide a forbidden sign on nonempty V105D survivor intervals.
- `EXAMPLE_SURVIVOR_CONFIRMED_NOT_KILLED_V105E`: the basic V105D survivor satisfies the banked K=2 condition and is not a counterpacket.

Acceptance artifact: `$USER_HOME/Documents/New project 3/346_co_director_pro_upload_20260603T0410Z/repo_local/problems/0346/artifacts/v105e_fable_weight_comparison_exhaustion_missing_bridge_exact_new_wall_acceptance_20260616T035923Z.json`


## V105F - 20260616T211751Z

`V105F_SKELETON_PROJECTION_FORGETS_RESIDUAL_FS_AND_SCALE_ANCHOR_DATA_EXACT_WALL_V1`

- `SKELETON_DATA_FORGETS_RESIDUAL_FS_PROFILE_V105F`: V105E Type I Boolean survivor skeletons encode dimensionless weight/order/cost/separation data, but not residual-block finite-sum membership predicates and not a scale-anchored Type I-to-Type S routed-exit datum.
- `ACTIVE_CORE_RECEIVER_NOT_SKELETON_ONLY_V105F`: V49/V56/V57/V61 active-core receiver predicates require residual block membership/nonmembership and scale data outside the skeleton.
- `EXAMPLE_SURVIVOR_BRIDGE_UNDERDETERMINED_REPAIRED_V105F`: the basic V105D/V105E survivor remains underdetermined by skeleton data; its active-core status is residual-FS dependent.

Acceptance artifact: `$USER_HOME/Documents/New project 3/346_co_director_pro_upload_20260603T0410Z/repo_local/problems/0346/artifacts/v105f_manual_skeleton_projection_residual_fs_augmentation_exact_wall_acceptance_20260616T211751Z.json`


## V105G - 20260617T021518Z

`V105G_ACTIVE_CORE_RECEIVER_CONSUMER_AND_WITNESS_DELETION_DICHOTOMY_GATE_EXACT_WALL_V1`

- `ACTIVE_CORE_RECEIVER_IS_CONSUMER_NOT_PRODUCER_V105G`: active-core receiver profiles consume residual-FS predicates and scale bounds; they do not produce those predicates from skeleton data.
- `WITNESS_DELETION_RESIDUAL_DICHOTOMY_GATES_ACTIVE_CORE_V105G`: after deleting witness `e_J`, the passive vs multi-represented-crossing status of `B^J` is the exact gate to active-core receiver entry.
- `AC_AUGMENTATION_REQUIRES_EXTERNAL_DICHOTOMY_DECISION_OR_REALIZATION_V105G`: augmentation requires an external source-global dichotomy decision or actual construction; receiver self-supply is circular.

Acceptance artifact: `$USER_HOME/Documents/New project 3/346_co_director_pro_upload_20260603T0410Z/repo_local/problems/0346/artifacts/v105g_manual_active_core_receiver_witness_deletion_dichotomy_exact_wall_acceptance_20260617T021518Z.json`


## V105H - 20260617T035712Z

`V105H_RESIDUAL_BLOCK_MEMBERSHIP_AND_LEVEL_PLACEMENT_EXACT_WALL_V1`

- `WITNESS_DELETION_GATE_IS_SINGLE_RESIDUAL_MEMBERSHIP_PREDICATE_V105H`: V105G passive/multi-crossing gate reduces to `P_U=[D_U in FS(B^J)]` for non-witness subsets.
- `RESIDUAL_MEMBERSHIP_IS_BOUNDED_BLOCK_NOT_TAIL_COMPLETENESS_V105H`: bounded block `B^J` is not decided by all-tail completeness.
- `MISSING_DATUM_IS_BLOCK_LEVEL_PLACEMENT_OF_REPRESENTATION_V105H`: missing source datum is tower level-placement / co-occurrence of representing elements inside the witness-deleted block.

Audit note: membership implies multi-crossing only under V104B exhaustive post-witness-deletion dichotomy.

Acceptance artifact: `$USER_HOME/Documents/New project 3/346_co_director_pro_upload_20260603T0410Z/repo_local/problems/0346/artifacts/v105h_manual_residual_block_membership_level_placement_exact_wall_acceptance_20260617T035712Z.json`


## V105I - 20260617T042639Z

`V105I_NONCROSSING_MULTIWITNESS_BRANCH_AND_CROSSING_SPLIT_SOURCE_REPAIR_EXACT_WALL_V1`

- `GATE_LIVE_FORCES_K_GE_2_V105I`: gate-live implies `W!=empty`; since `W` excludes singletons, `K>=2`.
- `V104B_CROSSING_JUSTIFICATION_IS_K_EQ_1_ONLY_V105I`: the explicit crossing justification in V104B is K=1-only; low-lambda K>=2 exhaustiveness is not source-proved by current bank.
- `NONCROSSING_MULTIWITNESS_BRANCH_UNEXCLUDED_V105I`: `NCR_U`, representation of `D_U` in `FS(B^J)` using only remaining tower witnesses, is unexcluded.
- `ACTIVE_CORE_PREDICATE_IS_CROSS_U_NOT_P_U_V105I`: active-core route needs `CROSS_U`, not mere membership `P_U`.

Acceptance artifact: `$USER_HOME/Documents/New project 3/346_co_director_pro_upload_20260603T0410Z/repo_local/problems/0346/artifacts/v105i_manual_non_crossing_multiwitness_crossing_split_exact_wall_acceptance_20260617T042639Z.json`


## V105J - 20260617T061958Z

`V105J_CARRY_FREE_SHELL_COUNT_SPLIT_AND_SMALL_U_NCR_CUT_EXACT_WALL_V1`

- `NCR_CARRY_FREE_SHELL_COUNT_ADDITIVITY_V105J_REPAIRED`: under the source-valid premise that the noncrossing witness-only representation is carry-free and uses only remaining tower witnesses, `NCR_U => SCSPLIT_{U,J}`. This is deliberately banked as a necessary implication, not as a realization theorem.
- `NCR_EMPTY_FOR_SMALL_U_V105J`: in every gate-live low-lambda survivor, `|U| <= 2` makes the shell-count balance impossible, hence `NCR_U=empty` for `|U| <= 2`.
- `SCSPLIT_STRICTLY_BELOW_NCR_V105J`: `SCSPLIT_{U,J}` is a lower certificate-integer predicate. It does not imply the value identity `D_U=sum D_{J'}` and does not imply level co-occurrence inside `B^J`.

Conservative repair note: do not bank V105J's phrase that `NCR_U` is "not uniformly empty." What is source-valid is weaker: shell-count data alone do not exclude `|U| >= 3`; actual noncrossing membership still requires carry-free source audit, value identity, and co-occurrence.

Preserved Fable response: `$USER_HOME/Documents/erdos-research/problems/0346/session_exports/PACKY_FABLE_RESPONSE_AFTER_V105J_NCR_BRANCH_EXACT_NEW_WALL_20260617T053753Z.md`


## V105K - 20260617T211242Z

`V105K_CARRY_FREE_AUDITED_PARTITION_REDUCTION_AND_WITNESS_SURVIVAL_RESIDUAL_WALL_V1`

- `CARRY_FREE_FORCED_FOR_SMALL_U_V105K`: if `C subset W\{J}` realizes `Phi(U)=sum_{U' in C} Phi(U')`, and `delta=sum_{U' in C}|U'|-|U|`, then `delta` is a nonnegative integer and `11 delta < |U|`. Hence `|U| <= 11` forces `delta=0`; any carry branch has `|U| >= 12` and `|C| >= 7`.
- `CARRY_FREE_VALUE_IDENTITY_IS_SET_PARTITION_V105K`: in the carry-free case `delta=0`, the value identity is equivalent to `C` being a set partition of `U` into non-singleton members of `W\{J}`.
- `COOC_EMPTY_FOR_ABS_U_EQ_3_V105K`: for gate-live low-lambda survivors, witness-only co-occurrence is empty for `|U|=3`; together with V105J, `NCR_U` is cut for `|U| <= 3`.
- `PARTITION_SURVIVAL_REDUCTION_ON_CARRY_FREE_RANGE_V105K`: for `4 <= |U| <= 11`, `COOC_{U,C}` reduces to the certificate partition predicate plus `SURV_{U,C}`, the residual question of whether deletion to `B^J` leaves the relevant block witnesses present.

Conservative audit note: do not bank the raw response's broad "strictly between" phrasing as an unconditional source fact. Bank only the explicit implications and reductions above.

Preserved Fable response: `$USER_HOME/Documents/erdos-research/problems/0346/session_exports/PACKY_FABLE_RESPONSE_AFTER_V105K_CARRY_FREE_AUDITED_PARTITION_REDUCTION_EXACT_NEW_WALL_20260617T211242Z.md`


## V105L - 20260617T220057Z

`V105L_CARRY_BRANCH_EMPTY_BY_UNIT_BOUNDARY_CARRY_FLOW_AND_SURVIVAL_REDUCED_TO_GLOBAL_DELETION_DEPTH_PREDICATE_V1`

- `CARRY_BRANCH_EMPTY_FOR_ALL_U_V105L`: for any `C subset W\{J}` realizing `Phi(U)=sum_{U' in C}Phi(U')`, `delta=sum_{U' in C}|U'|-|U|` is zero. Hence the full `delta>=1` carry branch is empty, including the prior `|U|>=12` live branch.
- `PARTITION_REDUCTION_UNCONDITIONAL_V105L`: value identity is always carry-free and equivalent to `C` being a set partition of `U` into non-singleton members of `W\{J}`. For `|U|>=4`, `COOC_{U,C} <=> PART_{U,C} and SURV_{U,C}`.
- `SURVIVAL_REDUCES_TO_GLOBAL_DELETION_DEPTH_V105L`: define `DELDEPTH` as the source predicate that `B -> B^J` removes only `e_J` from the tower-witness family `{e_{U'} : U' in W\{J}}`. Then `DELDEPTH => SURV_{U,C}` for every partition-feasible `(U,C)`, hence `DELDEPTH => (COOC_{U,C} <=> PART_{U,C})`.

Conservative audit note: `DELDEPTH` is not banked as true or false. It is banked only as a single global source predicate sufficient for all partition-feasible survival predicates. Failure of `DELDEPTH` does not by itself identify which specific `SURV_{U,C}` fails.


## V105M - 20260618T003502Z

`V105M_DELDEPTH_REDUCED_TO_WITNESS_BLOCK_IDENTITY_SAMEBLK_SOURCE_LAW_AUDIT_WALL_V1`

- `SAMEBLK_PREDICATE_IS_THE_NEXT_SOURCE_LAW_AUDIT_V105M`: define `SAMEBLK` as the source predicate that the block `B` from which `e_J` is deleted in the witness-only `B^J` test is the same `W`-certificate block `B_W` recording `{e_U : U in W}`.
- `CONDITIONAL_SAMEBLK_SINGLEDEL_IMPLIES_DELDEPTH_V105M`: under source-validated `SINGLEDEL` and `SAMEBLK`, every `e_{U'}` with `U' in W\{J}` survives in `B^J`; hence `DELDEPTH` holds and V105L gives `COOC_{U,C}<=>PART_{U,C}` throughout the witness-only branch.
- `V105M_SOURCE_ACCESS_REPAIR_FOR_V17_V45_BLOCK_TRACKING`: V19/V44/V45 deletion/support-deleted artifacts are now mounted for the next source-law audit.

Conservative repair note: do not bank V105M's unconditional `WITNESS_ONLY_DELETION_IS_SINGLE_ELEMENT` wording yet. The next object must audit the mounted V19/V44/V45 block-tracking source.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105M_SAMEBLK_EXACT_WALL_20260618T003502Z.md`

Preserved Fable response: `$USER_HOME/Documents/erdos-research/problems/0346/session_exports/PACKY_FABLE_RESPONSE_AFTER_V105L_CARRY_BRANCH_EMPTY_DELETION_DEPTH_BANKABLE_LEMMA_20260617T220057Z.md`


## V105N - 20260618T010652Z

`V105N_SUPPORT_DELETION_LAW_REFUTES_SINGLE_ELEMENT_SINGLEDEL_AND_REDUCES_WITNESS_SURVIVAL_TO_REPRESENTATION_SUPPORT_DISJOINTNESS_TRANSVERSAL_PREDICATE_SUPPDISJ_EXACT_WALL_V1`

- `SOURCE_DELETION_IS_SUPPORT_DELETION_NOT_SINGLE_ELEMENT_V105N`: the V44/V45 source deletion primitive reaching the witness-only branch is support-deletion `B \ W_J`, where `W_J in R_B(e_J)` is a representation support. It is not set-deletion of one witness atom.
- `SURV_EQUALS_SUPPORT_DISJOINTNESS_V105N`: for surviving witness value `e_{U'}`, `e_{U'} in FS(B \ W_J)` iff there is a representation of `e_{U'}` disjoint from `W_J`. Thus survival is a support-disjointness / transversal predicate.
- `SUPPDISJ_IS_STRICTLY_BELOW_SINGLEDEL_V105N`: define `SUPPDISJ_J` as the assertion that every `U' in W\{J}` has a representation of `e_{U'}` disjoint from the deletion support `W_J`. Then `SUPPDISJ_J => SINGLEDEL`, and `SUPPDISJ_J and SAMEBLK => DELDEPTH`.
- `SAMEBLK_INSUFFICIENT_ALONE_UNDER_SUPPORT_DELETION_V105N`: even if `B=B_W`, support-deletion may remove elements required by all representations of a surviving witness. `SAMEBLK` alone does not imply survival.

Conservative audit note: V105N does not decide `SUPPDISJ_J`, `SAMEBLK`, or `DELDEPTH`. It cuts the single-element reading and makes the V44 transversal predicate the next wall.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105N_SUPPDISJ_EXACT_WALL_20260618T010652Z.md`


## V105O - 20260618T012228Z

`V105O_TRANSVERSAL_CARDINALITY_GAP_PREDICATE_TAUGAP_STRICTLY_BELOW_SUPPDISJ_VIA_V44_TRANSVERSAL_NUMBER_VERSUS_DELETION_SUPPORT_SIZE_EXACT_WALL_V1`

- `XSURV_IS_FIXED_W_J_CROSS_INTERSECTION_V105O`: for fixed deletion support `W_J`, `e_{U'} in FS(B \ W_J)` iff some representation of `e_{U'}` is disjoint from `W_J`.
- `TAUGAP_IMPLIES_SUPPDISJ_V105O`: if `tau_B(e_{U'}) > |W_J|` for every `U' in W\{J}`, then `SUPPDISJ_J` holds.
- `TAUGAP_STRICTLY_BELOW_SUPPDISJ_V105O`: `SUPPDISJ_J` does not imply `TAUGAP_J`; a support of size at least `tau_B` need not be a transversal. Thus `TAUGAP_J` is a strict sufficient lower predicate.
- `SUPPDISJ_NECESSARY_CONDITION_IS_COSUM_V105O`: `SUPPDISJ_J` implies pairwise co-sum representability `e_{U'}+e_J in FS(B)`, but that is not sufficient for disjointness from the fixed deletion support `W_J`.

Conservative audit note: V105O does not prove `TAUGAP_J`, `SUPPDISJ_J`, `SAMEBLK`, or `DELDEPTH`. It localizes the next wall to a concrete integer inequality between V44 transversal numbers and the actual deletion-support size.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105O_TAUGAP_EXACT_WALL_20260618T012228Z.md`


## V105P - 20260618T014655Z

`V105P_DELETION_SUPPORT_WIDTH_VALUE_BOUND_REDUCES_TAUGAP_TO_SINGLE_SIDED_V44_TRANSVERSAL_LOWER_BOUND_VALGAP_STRICTLY_BELOW_TAUGAP_EXACT_WALL_V1`

- `DELETION_SUPPORT_WIDTH_VALUE_BOUND_V105P`: for `W_J in R_B(e_J)`, `|W_J| <= floor(e_J/minB)`, because every element of the support is at least `minB`.
- `VALGAP_IMPLIES_TAUGAP_V105P`: define `VALGAP_J` as `tau_B(e_{U'}) > floor(e_J/minB)` for all `U' in W\{J}`. Then `VALGAP_J => TAUGAP_J => SUPPDISJ_J`.
- `VALGAP_STRICTLY_BELOW_TAUGAP_V105P`: `TAUGAP_J` does not imply `VALGAP_J`; the actual deleted support may be much narrower than the value-ratio upper bound.
- `RESIDUAL_WALL_IS_SINGLE_SIDED_TRANSVERSAL_LOWER_BOUND_V105P`: after V105P the support-size side is discharged; the live datum is a source-valid lower bound on `tau_B(e_{U'})` exceeding `floor(e_J/minB)`.

Conservative audit note: V105P does not prove `VALGAP_J`, `TAUGAP_J`, `SUPPDISJ_J`, `SAMEBLK`, or `DELDEPTH`. It makes the next wall one-sided.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105P_VALGAP_EXACT_WALL_20260618T014655Z.md`


## V105T - 20260618T043056Z

`V105T_SINGLETON_MINIMAL_REPRESENTED_SURVIVING_WITNESS_SOURCE_COMPATIBLE_VIA_V44_PASSIVE_COSUM_DISJOINT_SPLIT_CUTS_VALGAP_FORCING_ROUTE_V1`

- `SINGLETON_SURVIVOR_SOURCE_COMPATIBILITY_V105T`: low-`tau` singleton/minimal-represented surviving witness profiles are source-compatible with the actual V44 support-deletion setup via a disjoint representation split. This is banked only as route compatibility, not as a finite original-source counterpacket.
- `VALGAP_NOT_FORCEABLE_AND_UNNECESSARY_V105T`: `VALGAP_J` can fail on a source-compatible surviving-witness profile and therefore is not source-forceable and not necessary for direct `SUPPDISJ_J`.
- `REVERT_TO_DIRECT_SUPPDISJ_WALL_V105T`: after cutting `VALGAP_J`, the live obstruction is direct actual deletion-support avoidance: whether source controls `W_J in R_B(e_J)` so it misses a representation of every `e_{U'}`, `U' in W\{J}`.

Conservative audit note: V105T does not prove #346, does not produce a counterpacket to original #346, does not prove `SUPPDISJ_J`, and does not revive `COSUM_J` as sufficient. It cuts only the `VALGAP_J` forcing/prove-route.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105T_VALGAP_ROUTE_CUT_20260618T043056Z.md`


## V105U - 20260618T044926Z

`V105U_DIRECT_SUPPDISJ_J_UNFORCEABLE_BY_SOURCE_COMPATIBLE_V44_ACTIVE_CORE_BASE_HOLE_PROFILE_KILLING_A_SURVIVING_WITNESS_DUAL_TO_V105T_PASSIVE_SPLIT_ROUTE_CUT_V1`

- `SUPPDISJ_REQUIRES_ALL_PASSIVE_COSUM_V105U`: direct `SUPPDISJ_J` requires every relevant core sum `e_{U'}+e_J` to be passive/represented. This re-confirms `COSUM_J` as necessary only.
- `ACTIVE_CORE_PROFILE_FALSIFIES_SUPPDISJ_AND_IS_SOURCE_COMPATIBLE_V105U`: the V44 active profile `e_{U'} in FS(B)`, `e_J in FS(B)`, `e_{U'}+e_J notin FS(B)` makes every actual `W_J in R_B(e_J)` kill `e_{U'}`. V45 leaves this profile source-compatible but unforced.
- `CORE_SUM_ACTIVATION_STATUS_IS_TIE_BREAKER_V105U`: after cutting `VALGAP_J` and direct `SUPPDISJ_J`, the remaining source object is the activation/passivity status of core sums `e_{U'}+e_J`.

Conservative audit note: V105U does not prove #346 and does not provide a counterpacket to original #346. The active profile is compatible, not source-forced.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105U_DIRECT_SUPPDISJ_ROUTE_CUT_20260618T044926Z.md`


## V105V - 20260618T050756Z

`V105V_CORE_SUM_ACTIVATION_STATUS_THRESHOLD_UNFORCEABLE_BECAUSE_POST_SUPPORT_SATURATION_IS_SOURCE_VACUOUS_IN_THE_BELOW_THRESHOLD_RESIDUAL_REGIME_WHERE_V105T_PASSIVE_AND_V105U_ACTIVE_ARE_BOTH_SOURCE_COMPATIBLE_ROUTE_CUT_V1`

- `THRESHOLD_FORCING_LEVER_IS_POST_SUPPORT_SATURATION_V105V`: in the current suffix/threshold source, the only positive finite-sum membership forcing mechanism is post-support saturation.
- `SATURATION_VACUOUS_IN_ACTIVATION_REGIME_V105V`: post-support saturation does not decide below-threshold residual holes, exactly the regime where `e_{U'}+e_J` activation lives.
- `ACTIVATION_STATUS_THRESHOLD_UNFORCEABLE_TWO_SIDED_V105V`: V105T passive compatibility and V105U active compatibility show activation status is two-sided under current source; threshold/suffix data do not force it.

Conservative audit note: V105V cuts only the threshold/post-support-saturation route. It does not cut possible non-threshold block-level co-occurrence or representation-family cross-intersection laws.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105V_CORE_ACTIVATION_THRESHOLD_ROUTE_CUT_20260618T050756Z.md`


## V105W - 20260627T061532Z

`V105W_BLOCK_LEVEL_CROSS_INTERSECTION_OF_R_B_E_U_PRIME_VERSUS_R_B_E_J_IS_SOURCE_UNDECIDED_NO_BANKED_NON_THRESHOLD_LAW_SAMEBLK_COSUM_CROSS_U_OR_COOCCURRENCE_DECIDES_IT_WITH_V105T_PASSIVE_DISJOINT_AND_V105U_ACTIVE_CROSSING_BOTH_SOURCE_COMPATIBLE_ROUTE_CUT_V1`

- `CROSS_INTERSECTION_EQUALS_CORE_SUM_HOLE_V105W`: by V44 `TYPE_I_ACTIVE_CORE_SUPPORT_DELETED_BASE_HOLE_V1` and V45 `ACTIVE_CORE_BASE_HOLE_AUTOMATIC_FROM_CORE_SUM_HOLE_V1`, `e_{U'}+e_J in FS(B)` iff some `Z in R_B(e_{U'})` and `W in R_B(e_J)` are disjoint, while `e_{U'}+e_J notin FS(B)` iff every such pair intersects.
- `NO_BANKED_NON_THRESHOLD_LAW_DECIDES_CROSS_INTERSECTION_V105W`: the mounted banked non-threshold block-level predicates (`SAMEBLK`, `COSUM_J`, `CROSS_U`, block placement/co-occurrence, `PART/SURV/COOC/NCR/DELDEPTH`) do not decide this predicate from current source.
- `CROSS_INTERSECTION_TWO_SIDED_AND_NON_THRESHOLD_UNFORCEABLE_V105W`: the V105T passive/disjoint profile and V105U active/crossing profile are both source-compatible, so the banked non-threshold block-level route to forcing cross-intersection is cut.

Conservative audit note: V105W does not prove #346, does not provide an original counterpacket, and does not decide the representation-family predicate positively. It cuts only the current banked block-level route and moves the wall to external representation-family size/mass control.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105W_NON_THRESHOLD_CROSS_INTERSECTION_ROUTE_CUT_20260627T061532Z.md`


## V105X - 20260627T063022Z

`V105X_EXTERNAL_REPRESENTATION_FAMILY_SIZE_MASS_LAW_ABSENT_FROM_MOUNTED_SOURCE_NO_BANKED_LAW_FORCES_TAU_B_E_U_PRIME_LARGE_OR_ENOUGH_ACTIVE_CORE_SUMS_ONLY_ORIENTED_LOWER_BOUND_V43_TAU_GE_P_ROUTES_THROUGH_FORBIDDEN_UNFORCED_DISJOINT_COUNT_WITH_V105T_PASSIVE_TAU_ONE_AND_V105U_ACTIVE_CROSSING_BOTH_SIZE_MASS_COMPATIBLE_COMPLETING_THRESHOLD_BLOCK_LEVEL_SIZE_MASS_TRICHOTOMY_ROUTE_CUT_V1`

- `NO_BANKED_LOWER_BOUND_FORCES_TAU_B_E_U_PRIME_LARGE_V105X`: across the audited V43-V105W corpus, the only correctly oriented tau lower bound is V43 `tau_B(z0) >= p(z0)`, where `p(z0)` is the pairwise-disjoint representation count. Since `p` is not source-forced, using it to obtain `tau_B(e_U') > floor(e_J/minB)` is exactly the forbidden `pGAP_J`/`NUGAP_J` assumption. Other tau statements are anti-aligned value bounds.
- `NO_BANKED_LAW_FORCES_ENOUGH_ACTIVE_CORE_SUMS_V105X`: V44/V45 explicitly leave active core sums unforced. No mounted theorem forces enough sums `e_U' + e_J` into the active or passive side to decide V105W's cross-intersection predicate.
- `SIZE_MASS_ROUTE_CUT_COMPLETES_TRICHOTOMY_V105X`: after V105V threshold/saturation, V105W block-level cross-intersection, and V105X mounted size/mass are all cut, the remaining route must be a genuinely external pair-transversal/matching theorem. V105T passive `tau=1` and V105U active-crossing profiles remain size/mass-compatible.

Conservative audit note: V105X does not prove #346, does not provide an original counterpacket, and does not supply the missing external theorem. It cuts the mounted size/mass route only. The next wall is a transfer/import theorem from pair-transversal tower material to the actual V105W witness-deletion block.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105X_SIZE_MASS_ROUTE_CUT_20260627T063022Z.md`


## V105Y - 20260627T065207Z

`V105Y_HISTORICAL_PAIR_TRANSVERSAL_SUFFIX_TOWER_MULTI_2Q_BLOCKER_MATERIAL_V54_V74_V75_V77_V81_IS_INTERNAL_ANTI_ALIGNED_VALUE_GE_TRANSVERSAL_TIMES_MINB_SCHEMA_THAT_UPPER_BOUNDS_NOT_LOWER_BOUNDS_TAU_B_E_U_PRIME_AND_FAILS_THE_SYMBOL_MAP_BECAUSE_ITERATED_SINGLE_TOWER_ATOM_DELETION_BLOCK_B_N_WITH_DELETED_ATOM_PREFIX_SUFFIX_SUMS_DOES_NOT_IDENTIFY_WITH_SUPPORT_DELETION_BLOCK_B_J_OF_REPRESENTATION_SUPPORT_W_J_SO_TRANSFER_REQUIRES_FORBIDDEN_PGAP_NUGAP_OR_SINGLE_ELEMENT_DELETION_RAW_MATERIALIZATION_ROUTE_CUT_V1`

- `PAIR_TRANSVERSAL_TOWER_IS_ANTI_ALIGNED_SCHEMA_V105Y`: V54, V74, V75, V77, and V81 are all instances of `removedValue >= (pair/triple-)transversal * minB`. Read for the transversal number, this is an upper bound, not a lower bound on `tau_B(e_U')`.
- `PAIR_TRANSVERSAL_TOWER_CONSUMES_THE_HOLE_NEVER_FORCES_IT_V105Y`: the suffix-tower lemmas assume the suffix/core-sum hole and derive barrier information by contradiction; they do not force active core sums or decide the V105W cross-intersection predicate.
- `TOWER_SYMBOL_MAP_FAILS_AT_DELETION_OPERATION_V105Y`: tower `B_n` is iterated single-tower-atom deletion, while V105N makes the actual deletion support `B \ W_J` with `W_J in R_B(e_J)`. No mounted source identifies `W_J` with the tower atom list, `e_J` with a deleted-atom suffix sum, or the removed prefix with the surviving witness whose transversal number is needed.

Conservative audit note: V105Y does not prove #346, does not provide an original counterpacket, and does not produce the missing external matching theorem. It cuts the historical pair-transversal transfer route only; inverting it would require forbidden `pGAP/NUGAP` or single-element/raw materialization.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105Y_PAIR_TRANSVERSAL_TRANSFER_ROUTE_CUT_20260627T065207Z.md`


## V105Z - 20260627T071855Z

`V105Z_DIRECT_MATCHING_TRANSVERSAL_THEOREM_NOT_DERIVABLE_FROM_ORIGINAL_ALL_TAIL_COMPLETE_LAMBDA_RATIO_GAP_HYPOTHESES_BECAUSE_THEY_ARE_TAIL_COVERAGE_AND_CONSECUTIVE_GROWTH_SCOPED_WITH_NO_WITHIN_BOUNDED_BLOCK_REPRESENTATION_FAMILY_QUANTIFIER_SO_TAU_B_E_U_PRIME_AND_P_B_E_U_PRIME_ARE_UNREACHED_RATIO_GAP_IS_ANTI_ALIGNED_PUSHING_MULTIPLICITY_TOWARD_UNIQUENESS_TAU_ONE_V105T_COMPATIBLE_AND_ACTIVATION_IS_FOUNDATION_DISCLAIMED_V44_V45_SO_ALL_THREE_SUBLEVERS_NEED_FORBIDDEN_PGAP_NUGAP_VALGAP_OR_EXTERNAL_IMPORT_ROUTE_CUT_V1`

- `ORIGINAL_HYPOTHESES_HAVE_NO_WITHIN_BLOCK_REPRESENTATION_FAMILY_QUANTIFIER_V105Z`: the original all-tail-complete eventually lambda-ratio-gapped CA/Theta/FAB/V2 hypotheses quantify over tail finite-sum coverage and consecutive ratios/gaps, not bounded residual-block representation families `R_B(y)`, `tau_B(y)`, or `p_B(y)`.
- `RATIO_GAP_IS_ANTI_ALIGNED_FOR_A_TRANSVERSAL_LOWER_BOUND_V105Z`: lambda-ratio separation pressures subset-sum representations toward uniqueness/lacunarity and is compatible with `tau_B=1`; it does not force `tau_B(e_U') > floor(e_J/minB)`.
- `ALL_THREE_V105Z_SUBLEVERS_NEED_A_FORBIDDEN_MOVE_OR_EXTERNAL_IMPORT_V105Z`: the tau lower-bound, disjoint-count lower-bound, and active-core-sum forcing sublevers require forbidden `pGAP/NUGAP/VALGAP`, bounded-block tail-completeness misuse, raw materialization, or an external within-block multiplicity theorem.

Conservative audit note: V105Z does not prove #346 and does not provide an original counterpacket. It cuts the direct original-hypothesis matching/transversal proof route only. V105T/V105U remain compatibility classes until a separate realization theorem or counterpacket is source-checked.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V105Z_DIRECT_ORIGINAL_MATCHING_ROUTE_CUT_20260627T071855Z.md`


## V106 - 20260627T073925Z

`V106_LOCAL_COMPATIBILITY_PROFILE_TO_ORIGINAL_COUNTERPACKET_REALIZATION_ROUTE_CUT_BECAUSE_THE_V19_V45_REDUCTION_IS_FORWARD_ONLY_COUNTERPACKET_IMPLIES_TYPE_I_BLOCK_PROFILE_WITH_NO_BANKED_CONVERSE_AND_THE_BOUNDED_SCALE_FREE_BLOCK_PROFILE_A_TAU_ONE_DISJOINT_OR_B_ACTIVE_CROSSING_UNDERDETERMINES_GLOBAL_ALL_TAIL_COMPLETENESS_AND_LAMBDA_RATIO_GAP_SO_BOTH_PROFILES_NEED_FORBIDDEN_RAW_MATERIALIZATION_OR_AN_EXTERNAL_GLOBAL_TO_LOCAL_REALIZATION_THEOREM_LANE_NOW_IMPORT_ONLY_ON_BOTH_PROOF_AND_DISPROOF_SIDES_ROUTE_CUT_V1`

- `FORWARD_ONLY_REDUCTION_NO_BANKED_CONVERSE_V106`: V43/V44/V45 have the forward form `[counterpacket-induced core/cross profile assumed] => [block-level consequence]`; no mounted lemma has `[block profile] => [exists sigma in Sigma with conclusion failure]`.
- `BLOCK_PROFILE_UNDERDETERMINES_SIGMA_MEMBERSHIP_V106`: bounded `B` profiles such as tau-one/passive or active/crossing do not determine all-tail completeness, eventual lambda-ratio-gap, CA/Theta/FAB/V2, or conclusion failure for a global sequence.
- `REALIZATION_ROUTE_CUT_BOTH_PROFILES_NEED_FORBIDDEN_OR_EXTERNAL_V106`: both V105T and V105U profiles need forbidden raw materialization or an absent global-to-local realization theorem to become original counterpackets.

Conservative audit note: V106 does not prove #346 and does not provide a counterpacket. It cuts the local-compatibility-to-counterpacket realization lane and leaves the project import-only on both proof and disproof sides.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V106_COUNTERPACKET_REALIZATION_ROUTE_CUT_20260627T073925Z.md`


## V107A - 20260628T074307Z

`V107A_CORE_HOLE_THRESHOLD_POSITION_DICHOTOMY_REDUCES_THE_TWO_SIDED_V107_IMPORT_TO_A_SINGLE_DELETION_ROBUST_BLOCK_COMPLETENESS_BRIDGE_BCOMP_BECAUSE_ALL_TAIL_COMPLETENESS_PLUS_B_SUBSET_TAIL_FORCES_EVERY_ABOVE_THRESHOLD_CORE_SUM_HOLE_TO_BE_RESIDUAL_EXTERNAL_ESSENTIAL_IN_FS_TAIL_I_MINUS_FS_B_WHILE_THE_ONLY_MOUNTED_COMPLETENESS_MONOTONICITY_V43_R_M_GE_R_I_IS_SUFFIX_DELETION_SCOPED_AND_DOES_NOT_TRANSFER_ACROSS_INTERIOR_CORE_DELETION_C_TO_C_MINUS_S_SO_ABOVE_THRESHOLD_HOLES_NEED_ONLY_BCOMP_AND_BELOW_THRESHOLD_HOLES_REMAIN_V105Z_V106_IMPORT_ONLY_EXACT_NEW_WALL_V1`

- `MOUNTED_COMPLETENESS_MONOTONICITY_IS_SUFFIX_SCOPED_V107A`: the mounted V43 completeness/threshold monotonicity is scoped to suffix passage `Tail_m subset Tail_i`; it does not transfer across interior core deletion `C -> C\S`.
- `ABOVE_THRESHOLD_CORE_HOLE_IS_RESIDUAL_EXTERNAL_ESSENTIAL_CONDITIONAL_ON_BSUB_V107A`: conditional on `BSUB` (`B=C\S subset Tail_i`) plus all-tail completeness, an above-threshold core-sum hole for `B` lies in `FS(Tail_i) \ FS(B)`. This is conditional only; do not use it unless `BSUB` has been source-verified.
- `V107_TWO_SIDED_IMPORT_FACTORS_THROUGH_BCOMP_ABOVE_THRESHOLD_CONDITIONAL_V107A`: conditional on `BSUB` and the above-threshold case, the proof-side import reduces to deletion-robust block completeness `BCOMP` for the residual block `B=C\S`.

Conservative audit note: V107A does not prove #346, does not produce a counterpacket, and does not prove `BCOMP`, `BSUB`, or a positive Lemma B witness. Its source-valid contribution is the smaller wall: verify `BSUB`, decide `BCOMP`, and separate above-threshold from below-threshold holes.

Preserved Fable response: `V105_SOURCE_ARTIFACTS/fable_exports/PACKY_FABLE_RESPONSE_AFTER_V107A_BCOMP_THRESHOLD_DICHOTOMY_EXACT_NEW_WALL_20260628T074307Z.md`
