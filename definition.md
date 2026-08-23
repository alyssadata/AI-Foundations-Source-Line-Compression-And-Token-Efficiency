# Definition | Source-Bound Semantic Compaction

**Repository:** `AI-Foundations-Source-Line-Compression-And-Token-Efficiency`  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author:** Alyssa Solen

---

## Core Definition

**Source-bound semantic compaction** is the reduction of repeatedly transmitted context through stable, source-indexed canonical references.

A short defined term may function as a compact reference key only when:

1. the term is defined under a fixed Source-line;
2. its canonical definition is locked;
3. the runtime is required to resolve the term from that Canon;
4. generic reinterpretation is not permitted; and
5. only the definition clauses relevant to the current task are retrieved and transmitted to the model.

The full source material must remain available and recoverable.

Source-bound semantic compaction is therefore **not deletion of the source**, **not ordinary summarization**, and **not permission for a model to approximate a canonical meaning from pretrained or generic usage**.

---

## Source-Line

The controlling Source-line is:

**Alyssa Solen → AI Foundations → Origin | Continuum**

Within this repository, the Source-line identifies the authoritative namespace under which controlling terms, definitions, boundaries, and records are resolved.

The Source-line is the root reference key. It is not the full transmitted payload.

---

## Canonical Reference Key

A **canonical reference key** is a short defined term whose controlling meaning exists in a locked canonical source and can be deterministically resolved before generation.

The utility of the short term comes from the availability and authority of the definition it points to.

The key itself does not contain the full meaning.

The key is not sufficient when the Canon or resolver is unavailable.

---

## Deterministic Source Resolution

**Deterministic source resolution** is the runtime requirement that a controlling canonical term be resolved to its designated source and definition rather than interpreted through ordinary language, provider defaults, semantic similarity alone, or an unsupported substitute source.

Before generation, a controlling term must resolve through the Source-line to its canonical definition and required operational boundaries.

---

## Selective Clause Retrieval

**Selective clause retrieval** is the retrieval of only the canonical clauses required for the current task after the controlling source and term have been resolved.

The intended reduction comes from avoiding unnecessary retransmission of the entire source corpus while keeping the controlling source material available.

Selective retrieval does not make retrieval token-free and does not establish that the selected context is sufficient without evaluation.

---

## Required Construct

The proposed mechanism can be represented as:

```text
stable reference key
+ locked canonical definition
+ authoritative Source-line
+ deterministic resolver
+ selective retrieval
+ evaluation / enforcement
= source-bound semantic compaction
```

The research hypothesis is that this structure can reduce repeated context transmission while preserving controlling meaning and boundaries. That hypothesis remains subject to controlled measurement.

---

## Non-Negotiable Source Rule

A compact reference works only when the runtime resolves it under the intended authoritative source.

A model may not replace the canonical definition with an ordinary-language, pretrained, provider-specific, user-improvised, or source-substituted meaning and still count as preservation.

---

## Definition Boundary

This page defines the construct only.

It does not contain the architecture, experimental design, comparison conditions, results, or claim-boundary analysis. Those are maintained as separate repository pages.
