Try and solve 346 if possible.No internet.

You are continuing the Erdős #346 co-director proof audit in the same Pro project/chat. Use only the uploaded project sources, this chat context, and the Opus MAX adversarial response summarized below. Do not use internet or outside literature.

## Current Exact State

#346 is not solved. No counterpacket is banked. No positive Lemma B witness is banked.

You just returned:

`CLASSIFICATION: BANKABLE_LEMMA`

`OBJECT: V11_TOP_HOLE_HANDOFF_AND_UNIVERSAL_GEOMETRIC_SPLICE_WINDOW_CUT_V1`

Banked V11 items:

- `CONSTANT_RECONFIRMATION_V11`.
- `TOP_HOLE_HANDOFF_NO_COLLISION_V1`.
- `UNIVERSAL_GEOMETRIC_SPLICE_WINDOW_V1`.
- `LAMBDA_ONE_PLUS_INVERSE_SQRT_TWO_CUT_V1`.
- `UPDATED_BRANCH_RANGE_REDUCTION_V1`.

Current live wall after your V11 answer:

`FINITE_WINDOW_SUCCESSOR_GAP_SHADOW_BRANCH_CASCADE_IMPOSSIBILITY_OR_REALIZATION_V12`

First failed clause:

`NO_FINITE_WINDOW_SUCCESSOR_GAP_SHADOW_CASCADE_CAP`

Reduced live parameter range:

`1 < lambda <= 1 + min(eta_bar, 1/sqrt(2))`

Normalize the constant:

`c=(1-eta_bar)/eta_bar`, with `eta_bar in (1/2,1)`.

## New External Input To Audit

An independent Opus MAX adversarial/construction run returned the following classification:

`BANKABLE_LEMMA (carrying a ROUTE_CUT of the scalar/forced-clause impossibility direction, plus an EXACT_NEW_WALL). Not PROOF, not COUNTERPACKET.`

Its proposed object:

`TAIL_COMPLETENESS_SLACK_CRITERION_AND_FORCED_CLAUSE_REALIZATION_V11`

Main Opus claims:

1. `TAIL_COMPLETENESS_SLACK_CRITERION_V1`:
   For increasing positive integers `a_k`, `S_k=sum_{i<=k} a_i`, define Brown slack
   `g_k=S_k+1-a_{k+1}`.
   Opus claims:
   all-tail-complete iff `g_k -> +infinity`.

2. `RATIO_GAP_EXISTENCE_BOUNDARY_V1`:
   Opus claims all-tail-complete eventually-`lambda`-ratio-gapped sequences exist throughout `1<lambda<2`, e.g. `a_k=floor(rho^k)` with `lambda<=rho<2`, and no such sequences exist for `lambda>=2`.

3. `FORCED_CLAUSE_LAYER_REALIZATION_V1`:
   Opus claims the V10/V11 forced layer is realized by explicit infinite sequences for every `lambda<2`, so no impossibility can live in successor-gap shadows, persistent holes, or bounded/immediate redemption alone.

4. `SHADOW_PAIR_IS_COMPLEMENT_CONJUGATE_V1`:
   Opus claims `R-1+b` and `H_n-b` are complement-conjugates and cannot collide independently.

5. Opus proposes the next wall:
   `FINITE_SUM_BLOCK_SPLICE_COHERENCE_V12`
   and says the real obstruction must involve the special branch-start finite block data `C`, `J`, `R_-`, `q`, paired-cover, mirror interval, deletion/minimality constraints, not the generic forced layer.

## Director Concern / Required Repair

Do not accept Opus at face value.

The raw slack criterion as stated appears false without residue/modular conditions. For example, an eventually all-even increasing sequence with geometric ratio `<2` can have `g_k -> infinity` while every finite sum is even, so no tail is complete. Therefore:

- If there is a repaired Brown-type criterion, state it exactly.
- If the criterion is false as stated, classify that exact claim as rejected or route-cut.
- If `floor(rho^k)` is used as a realization, verify the exact cofinite completeness condition; do not infer from scalar slack alone.

## Target

Audit Opus MAX's V11 adversarial output against the current banked FAB1-FAB3/V2-V11 chain.

The goal is not to duplicate your V11 result. The goal is to decide what, if anything, is bankable from Opus and whether it changes the live V12 wall.

## Specific Questions

1. Is `TAIL_COMPLETENESS_SLACK_CRITERION_V1` true, false, or repairable? State the exact theorem with all needed hypotheses.

2. Is there a clean, bankable Brown/suffix completeness criterion relevant to all-tail completeness in this problem? If yes, give it exactly and say whether it changes V12.

3. Is Opus's `a_k=floor(rho^k)` realization actually all-tail-complete for any `rho in (1,2)`? If yes, prove with all residue conditions. If no, give the first failed clause.

4. Does Opus cut any part of the current route beyond what V10/V11 already cut? In particular, does it cut the forced-layer/successor-gap-shadow contradiction route only, or does it also cut some branch-specific V12 route?

5. Does Opus's proposed `FINITE_SUM_BLOCK_SPLICE_COHERENCE_V12` match, refine, or conflict with your `FINITE_WINDOW_SUCCESSOR_GAP_SHADOW_BRANCH_CASCADE_IMPOSSIBILITY_OR_REALIZATION_V12`?

6. Does the `SHADOW_PAIR_IS_COMPLEMENT_CONJUGATE_V1` claim add anything beyond your `TOP_HOLE_HANDOFF_NO_COLLISION_V1`, or is it already subsumed?

7. What is the exact next object after integrating only the valid parts of Opus?

## Forbidden Moves

- No internet.
- Do not treat computations as proof.
- Do not accept scalar slack as tail completeness unless the finite-sum residue/coverage condition is explicit.
- Do not call finite local compatibility a counterpacket.
- Do not reject prior banked Pro results unless you name the exact false clause.
- Do not use the old eta-inverted constant.
- Do not claim bounded redemption/immediate redemption is a contradiction.
- Do not reopen finite-only frontier-block contradiction.

## Allowed Exits

Your classification must be exactly one of:

- `PROOF`
- `COUNTERPACKET`
- `BANKABLE_LEMMA`
- `ROUTE_CUT`
- `EXACT_NEW_WALL`
- `REJECT_PRIOR_BANK`

## Required Artifact Format

Return:

1. `CLASSIFICATION:`
2. `OBJECT:`
3. `SHORT VERDICT:`
4. `OPUS CLAIM AUDIT:`
5. `PROOF / COUNTERPACKET / BANKABLE LEMMA / ROUTE CUT DETAILS:`
6. `FIRST FAILED CLAUSE:` if not a proof/counterpacket.
7. `BANKABLE ITEMS:` exact list, if any.
8. `REJECTED / REPAIRED OPUS ITEMS:` exact list.
9. `NEGATIVE BOUNDARIES:` exact list of what is not proved.
10. `NEXT EXACT OBJECT:` if not solved.

## Desired Outcome

Best useful answer:

- `BANKABLE_LEMMA` for a repaired Brown/suffix completeness criterion if true and relevant;
- `ROUTE_CUT` for Opus's overbroad slack criterion or forced-layer realization if false/overclaimed;
- `EXACT_NEW_WALL` if the valid integration strictly sharpens V12.

Worst useful answer:

- `EXACT_NEW_WALL` naming the smallest precise missing hypothesis needed to decide whether Opus's construction can instantiate the branch-start `C/J/R_-/q` data coherently.
