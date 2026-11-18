<!-- SPDX-License-Identifier: Apache-2.0 -->
# Repository agent policy

## Priority 0 — full-history superset-merge custody and last-checked rule (2026-11-18)

Every accepted fork evolves as a **backward-compatible optimized API/behavior superset** of applicable historical upstream and fork capabilities. Source/API/ABI, tests, platform/native lifecycle, formats, earlier fixes and measured optimizations must not be silently lost. Evaluate multiple candidate algorithms, old branches and PRs, and choose the best *proven* implementation using correctness, allocation, latency, throughput, concurrency and license compatibility; grow APIs additively. Before any merge, inspect Git ancestry back to the earliest reachable root across all relevant heads/tags, merged/closed/reverted PRs, both merge parents, renames/deletions and previously rejected bad commits; never rebase `develop`. Record per-ref last-checked date, exact SHA, scan scope/oldest ancestor, PR/branch coverage, previous verified SHA and findings in the canonical Synexia checkpoint ledger. A HEAD snapshot is only PARTIAL/PENDING. Use the established Synexia Maven/OpenRewrite recipes, exact-source history-loss and target compiler/behavior/native gates in accordance with each repository role. Prefer Apache-2.0 for **new separable first-party** code, retain applicable upstream/donor licenses and NOTICE, and never treat LLM-assisted atomization/patternization as automatic relicensing. Canonical instructions and explicitly PENDING 236-repo inventory: [com.synexia PR #18764](https://github.com/hsoliwal/com.synexia/pull/18764).



## Superset merge and history-audit rule (2026-11-18)

Read [.github/MERGE_RULE.md](.github/MERGE_RULE.md) before changing an existing implementation or integrating any branch or PR.
Preserve the supported additive API/behavior superset and select implementations by correctness, predictability, measured performance, then elegance.
Audit all reachable history back to every root, all branches/tags and all PR states for lost code or regressions; preserve append-only history.
Record actual UTC coverage and remaining work in [.github/HISTORY_AUDIT.tsv](.github/HISTORY_AUDIT.tsv); policy installation is not a completed source-history audit.
Prefer verified Apache-2.0 sources and independent implementations while preserving all existing third-party rights; LLM rewriting does not remove license obligations.
Detailed private recipe/proof records remain in canonical Synexia; the compact local policy and checkpoint make the rule discoverable here.
<!-- MERGE-SUPERSET-HISTORY-20261118-2 -->

## MOP SDK cross-repository agent read gate (2026-11-18)
<!-- MOP-AGENT-2026-11-18-1 -->
Before any source analysis, refactor, PR, merge, licensing decision, or history checkpoint, also read [AGENT.md](AGENT.md). It governs bidirectional atomization/patternization, documented contract-sealed atoms, additive best-of-best API supersets, complete available-history loss checks, dated last-verified proof, Apache-2.0 eligibility and upstream rights. Existing stronger project-specific and locked-canon constraints remain in force. Installation of this pointer does not establish that a source or historical audit has run.

# Repository agent policy

## Additive historical-convergence owner directive (2026-11-18)

Before a merge, loss repair or API enhancement, survey all accessible commits to history roots, all branches/tags, and paginated accepted/rejected/closed/merged PRs and head/merge refs. Compare actual pre/post class/member/atom source and tests: a merged PR or ancestry alone is not delivered code. Identify and restore lost working APIs, behavior and measured optimizations; never erase history to make a bad commit disappear.

Choose the strongest *compatible* correct algorithms and atoms from every qualifying revision; the outcome is an additive, backward-compatible superset. Preserve source/binary/reflective behavior, callbacks, concurrency, native lifetime, resource budgets and regression tests for this toolkit. All reusable atomization/patternization and Java/Maven/OpenRewrite recipes remain canonically in `hsoliwal/com.synexia`; this product fork receives only legitimate code/test postimages.

Prefer Apache-2.0 for separately original eligible contributions; preserve original upstream and per-file licenses (EPL/GPL/Apache/other), NOTICE, provenance and license exceptions. Algorithmic ideas may be independently reimplemented from lawful specifications, but LLM rewriting copyrighted code does not waive its rights or relevant patents.

Central last-checked checkpoint: `hsoliwal/com.synexia/docs/M3-SCALE/invariants/SYNEXIA-HISTORY-REVIEW-LAST-CHECKED.tsv`. Record exact checked SHA/date and root/ref/PR coverage; label unverified/lost-source reviews PARTIAL. Do not store history audit bundles in this clean product repository.

## MOP SDK — documented semantic atoms and machine-classified patterns (2026-11-18)

Before any source-changing task, follow the [canonical Synexia atom/pattern law](https://github.com/hsoliwal/com.synexia/blob/develop/docs/M3-SCALE/invariants/SYNEXIA-UNIVERSAL-API-ATOM-PATTERN-EVOLUTION-1.md) and [MOP SDK lattice proposal](https://github.com/hsoliwal/com.synexia/pull/18784). Descend repository -> project -> module -> package -> file -> declarations -> meaningful behavioral atoms; preserve original API/ABI, identity, effects, ordering, resource, native, serialization and concurrency contracts. Recognize existing algorithms/patterns by versioned catalogue ID, typed roles, applicability and proof. Where no qualified match exists, retain the code and register `UNKNOWN_ALGORITHM`, `UNKNOWN_PATTERN` or `UNPROVEN_MATCH` with source pin, owner/atom, effects, dependencies, rationale and evidence status. Link this typed residue from source-bound documentation or an **already supported** annotation; never create an uncompilable marker or invent an admitted pattern. Recompose upward through the actual affected dependency closure, with parallel independent file analysis and serial proof-gated canonical mutation. Preserve best-qualified additive history and source/provenance; pattern labels, hashes and LLM output are never equivalence proof. Canonical recipe, catalogue, evidence and correction memory stay in Synexia; clean product targets receive only qualified postimages. **Policy binding only**: full history, compiler, recipe, test, runtime and pattern coverage are NOT_RUN unless proven separately.
