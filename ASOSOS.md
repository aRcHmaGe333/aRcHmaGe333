# ASOSOS — A System of Systems of Systems

**Interconnected reuse of accumulated work, computation, software and developed capabilities.**

*Public design disclosure, 18 November 2026.*

## Purpose

Files, programs, machines, agents and people repeatedly reconstruct work that already exists. ASOSOS proposes connecting independent systems so that a result achieved in one context becomes available to other compatible contexts, and the relationships between cooperating systems themselves become reusable.

The design has three levels: **individual systems** performing specialized work; **systems of systems** combining those capabilities; and **ASOSOS**, recognizing and improving relationships between whole cooperating systems. The central unit is a *reusable achievement*, not necessarily a file or document.

This is a proposed integration of independent projects at different stages of development, not a claim that the complete architecture is implemented.

## One governing rule

**Reuse first, calculate later.** The existing Never Repeat development principle calls for retrieving a valid persisted result, computing only what changed, and preserving the new achievement. Its engineering precedents include memoization, incremental computation, DRY, and a single authoritative implementation with modular extensions.

ASOSOS should use established systems wherever they already do the work. Shared functions should have one authoritative implementation, with independent modules serving different purposes.

## Common operational description

A reusable achievement needs: identity; result or reconstruction method; dependencies and validity conditions; relationships to other resources; demonstrated outcome; provenance and permissions; cost; and applicable alternatives.

Exact content identity, operational equivalence and semantic similarity are distinct. The system selects reuse according to the task's actual conditions rather than similarity alone.

## UDF — representation, storage and retrieval

[Universal Data Fabric](https://github.com/aRcHmaGe333/udf) addresses shared chunks, manifests, content identity, locators, delta transfer, and reconstruction. Its prepared-cache concept makes a resource's retrieval plan available without keeping all bytes in memory. Its [Action → Outcome Cache](https://github.com/aRcHmaGe333/udf/blob/main/docs/compute-cache.md) already proposes mapping deterministic actions and relevant conditions to saved results.

ASOSOS and ECOmpile should use UDF's existing representation and retrieval functions rather than build a competing store. Across whole computers, compatible libraries, application assets and dependencies may be shared or reconstructed while each application retains its expected environment. Identical bytes and compatible executable components require different checks.

## ECOmpile — three forms of reuse

[ECOmpile](https://github.com/aRcHmaGe333/ECOmpile) can choose among:

1. **Result states:** deliver a completed verified outcome directly, or reuse its valid portion and compute the difference.
2. **Deterministic procedures:** convert repeated successful neural operations into ordinary executable code when repeated execution is cheaper than retaining separate result states.
3. **Cultivated instances:** reuse developed agent abilities and working-memory states, not just the last output.

Expensive computation may be replaced by a retained result; expensive retention of many results may be replaced by inexpensive code. Which path wins depends on correct delivery, cost, applicability and the likely reuse of an ability across future tasks.

[The current ECOmpile design](https://github.com/aRcHmaGe333/ECOmpile/blob/master/docs/never_repeat_principle.md) is an application of the already established Never Repeat principle, not an independent invention of that rule.

## ABCaps — reusable developed ability

[ABCaps](https://github.com/aRcHmaGe333/ABCaps) is concerned with an agent's acquired capability and the working state that enabled it. A successful log may be paired with the model version, tools, corrections and observed abilities that produced it. That experience can be used with the same model or a newer model; retained ability must be established through actual results.

Restoring a genuine runtime checkpoint, reconstructing performance from a log and transferring behavior to a different model are different operations. A transcript alone is not a copy of inaccessible hidden model state.

## TruMate — intellectual work and collective reuse

[TruMate](https://github.com/aRcHmaGe333/TruMate) processes intellectual material with source relationships, corrections and meaning intact. It may help people combine independently developed work, prepare publications under their own names, and selectively share results without disclosing entire private histories. ECOmpile supplies reusable execution and result delivery; TruMate supplies understanding and recombination of contributions.

## Machine-wide maintenance and software organization

A machine-aware system can maintain a usable account of components, versions, dependencies, faults, configurations and known working states. A successful repair can become a reusable operation for compatible machines, avoiding repeated diagnosis. Local execution, potentially through Gundam, is distinct from identifying a suitable repair.

Software and file organization similarly benefit from identifying shared components and preserving application-specific views of a reorganized store.

## Contributions, evidence and cooperation

[IPClaim](https://github.com/aRcHmaGe333/IPClaim) supplies the author's authorship declarations and cryptographic evidence tied to exact repository states. A timestamp is evidence of content existence at a date; it does not independently establish legal ownership, novelty or patent rights.

[ValueFlow](https://github.com/aRcHmaGe333/ValueFlow) concerns contribution economics and voluntary arrangements for shared value. Its independent development and permissions remain intact; no integration or adaptation is authorized by this disclosure.

Other complementary projects include [RATT](https://github.com/aRcHmaGe333/RATT) for independent reviews, [SIMEntity](https://github.com/aRcHmaGe333/SIMEntity) for continuing agent development, [NLLPM](https://github.com/aRcHmaGe333/NLLPM) for intent and result checking, [PiggyAI](https://github.com/aRcHmaGe333/PiggyAI) for service selection, and [LPS](https://github.com/aRcHmaGe333/LPS) for publication at different levels of detail. They remain independent unless an actual integration is established.

## Practical operation

For each requested outcome: locate an existing achievement; check its relevant conditions and permissions; choose direct delivery, deterministic execution, an established agent capability, partial adaptation, or new work; verify the actual result; preserve what has been achieved. Each successful connection can become useful to other systems.

The purpose is correct results at lower cost, wider reuse of accumulated knowledge, and more useful cooperation among people and machines. Development and discovery occur through real applications and practical integration.

## Established technical foundations

- [W3C PROV](https://www.w3.org/TR/prov-dm/) — provenance and derivation relationships.
- [FAIR principles](https://www.go-fair.org/fair-principles/) — machine-actionable discovery and reuse.
- [IPFS](https://docs.ipfs.tech/concepts/how-ipfs-works/) — content addressing.
- [Nix](https://nixos.org/guides/how-nix-works/) — reproducible software environments.
- [Bazel remote caching](https://bazel.build/remote/caching) — action-keyed computation reuse.
- [LangGraph persistence](https://docs.langchain.com/oss/python/langgraph/persistence) — durable execution state.
- [The Pragmatic Programmer](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/) — DRY.

These are related established techniques, not claims of new authorship. ASOSOS proposes their coordination with the independent systems identified above.

---

**Origin:** Author's discussions and prior project designs, consolidated 18 November 2026. Authorship evidence is provided by repository history and any independently verified timestamp proof associated with the published state. All rights reserved under the repository's applicable terms.
