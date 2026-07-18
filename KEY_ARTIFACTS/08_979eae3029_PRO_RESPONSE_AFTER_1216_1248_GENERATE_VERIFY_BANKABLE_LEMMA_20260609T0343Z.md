classification: **BANKABLE_LEMMA**

accepted_object:
`J42_TO_J43_CHUNKED_SECOND_EDGE_FROM_RECURSIVE_J41_FIRST_EDGE_EXTENSION_1216_1248_GENERATE_VERIFY`

accepted_local_classification:
`J42_TO_J43_EXTENSION_1216_1248_GENERATE_VERIFY_PASS`

required_hashes:

* Preflight Pro acceptance: `acff514e7d1e5c2a66232dca19da679f30dce4b507602e7e1fb5e169f4f8586c`
* Preflight script: `79d30804ad616ccd05613e783e74a6ddaa069bd4ccb74ba57799fe83aa730905`
* Preflight summary: `04b6b245960d0a3f94c388627f151134544958496fe2d008385c7fd02d5ca7f3`
* Preflight contract: `6a07749ab37760a848ab29bbc4458adda16c99eddb0c0b5272cd143968e21656`
* Preflight manifest: `9aefcd7e0144d549f2968198ee432cd5269c6aaa4d490dce75e9899349a44b21`
* Preflight report: `4c2226c42164a6cf9c150ba24e5129ac0e1e942a262816c498dff3421192a8b8`
* Preflight Pro md: `5fd0944fa1ed5bbb7dd8bc66b9c9f682b7918073d55dfcde0f844cac349a7cc9`
* Preflight Pro capture: `c1d60872100cdd160e85da2b486181f2fd9e18a6e888efaa21a113bc72c9ec93`
* Generate/verify script: `27f825fa5c64930db6bb6d9b4ee593d2be075f01f316457c3bba7c05111eb31b`
* Generated output gzip: `1f24b7ef25b4fb6885cacbff29a5ef605116cc268a7752f017b5534c57346788`
* Generate/verify progress: `ec69ae4a71c3f3047f77f18053bb58366eb1591cbf6a586fe060b396f6f9b71b`
* Generate/verify summary: `e2c839ddbc1ba3d5ec856ef5273bb23c43bff5c3887de19363378671ac898ed3`
* Generate/verify manifest: `1764b47fdd69eed31fcd9fb13608b8b8b2af40c8a9b60869e72c86e3866f67a1`
* Generate/verify report: `1be1e4c179e3749e35e8a2d5921c09a2646dbd5c1ae4a66e9bd6141191227578`
* Source cache: `d0c90d9f5c2e1d7593d0067cee8375f7fd254865d219e91c8e3763226cf7ee8b`
* Base window packet: `6389ab10ba1246a6e0c5a2c5f6e85541a0ce737fd696356908a763dc58c151b4`
* Upper window packet: `02e2270b394150fb6c8cd482580033be5a3b6cb19b9f9aabaa6d9bbafe51bc35`
* Wave821 manifest: `58c7bba1d3ea6502770f315ad24fb7959560d784df33dcff8cfc6c3a936c5da9`
* Wave821 composition piece count: `170424`
* Batch coverage digest: `c1b3cce9c4d24e58e81972d75d94c58a683e89dc2bdb5a35480ffd4fa4cd2509`
* External uploaded checksum anchor retained, not scope-widening: `88f9db1bf9b158e243e215a7c91269c20f78cc209439dd714c6cd62467e69db3` 

accepted_aggregate:

* Preflight dependency is accepted as Pro-banked: `J42_TO_J43_CHUNKED_SECOND_EDGE_FROM_RECURSIVE_J41_FIRST_EDGE_EXTENSION_1216_1248_PREFLIGHT`.
* That preflight authorized exactly this generated object: `J42_TO_J43_CHUNKED_SECOND_EDGE_FROM_RECURSIVE_J41_FIRST_EDGE_EXTENSION_1216_1248_GENERATE_VERIFY`.
* Generated coverage is exactly `source_range=[1216,1248)`, i.e. source indices `1216..1247` only.
* `source_row_count=32`
* `chunk_row_count=960`
* `total_rows=992`
* Row count check: `32+960=992`
* `total_source_nu_values_processed=1543778720`
* `total_second_edge_chunk_count=960`
* `total_second_edge_target_projected_count_sum=704`
* `component_mode=multi_component_contiguous_wave1109_first_edge`
* `component_count=8`
* `candidate_global_ordinal_range=[6576,6767]`
* `candidate_global_ordinal_count=192`
* Candidate arithmetic check: `6767-6576+1=192`
* Candidate adjacency check: prior banked prefix `[0,1216)` ended at candidate ordinal `6575`; this generated object starts at `6576`.
* `chunk_count_hist=[[20,16],[40,16]]`, giving `20*16+40*16=960`.
* `target_count_hist=[[20,16],[24,16]]`, giving `20*16+24*16=704`.
* `errors=[]`

accepted_component_totals:

* `wave882_source_1216_1220`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=166036464`
* `wave883_source_1220_1224`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=166053024`
* `wave884_source_1224_1228`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201939600`
* `wave885_source_1228_1232`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201952512`
* `wave886_source_1232_1236`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201964080`
* `wave887_source_1236_1240`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201949600`
* `wave888_source_1240_1244`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201943184`
* `wave889_source_1244_1248`: `source_count=4`, `chunk_row_count=120`, `target_projected_count_sum=88`, `source_nu_values_processed_sum=201940256`

Component checks: `8*4=32` source rows, `8*120=960` chunk rows, `8*88=704` target sum, and the component nu sums total `1543778720`. The source intervals are contiguous from `[1216,1220)` through `[1244,1248)` with no gap and no overlap.

independent_gzip_check:
PASS. The gzip sanity check agrees with the claimed object:

* `total JSONL rows=992`
* `J42_TO_J43_EXTENSION_SOURCE_ROW_V1 rows=32`
* `J42_TO_J43_SECOND_EDGE_CHUNK_ROW_V1 rows=960`
* source indices contiguous `1216..1247`
* component source counts exactly `4` for each of Wave882 through Wave889
* chunk histogram exactly `[[20,16],[40,16]]`
* target histogram exactly `[[20,16],[24,16]]`
* bad row formats count `0`
* source checkpoint gzip count `32`
* checkpoint source indices contiguous `1216..1247`
* progress line count `32`
* progress indices contiguous `1216..1247`

authorized_next_exact_object:
`J42_TO_J43_CHUNKED_SECOND_EDGE_FROM_RECURSIVE_J41_FIRST_EDGE_PREFIX_0000_1248_AUDIT`

first_failed_clause:
`null`

negative_boundaries_preserved:

* This banks only generated/verified finite row evidence for `[1216,1248)`.
* No `[0,1248)` prefix audit is claimed by this object.
* No full `[0,7056)` J42-to-J43 coverage is banked.
* No shifted QueryClass closure is banked.
* No phase closure is banked.
* No proof of #346 is banked.
* No counterpacket status is banked.
* No source-placeholder substitution, induction, periodicity, endpoint-only closure, raw profile materialization, dependency installation, Lean setup, or broader/nonadjacent generation is banked.
* The only next authorized object is the audit-only prefix object `[0,1248)`.

Durable artifact: [PRO_RESPONSE_AFTER_1216_1248_GENERATE_VERIFY_BANKABLE_LEMMA_20260609T0239Z.md](sandbox:/mnt/data/PRO_RESPONSE_AFTER_1216_1248_GENERATE_VERIFY_BANKABLE_LEMMA_20260609T0239Z.md)
Artifact sha256: `e9402379bc5f8ec9466c71e3fad7e46f83a7388b980bd58d8381428b709e4d4a`
