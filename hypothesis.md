# Research Hypotheses | Source-Line Compression and Token Efficiency

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author:** Alyssa Solen

---

## Primary Hypothesis

> A source-bound container using locked canonical definitions, deterministic reference resolution, and selective retrieval will require fewer repeated input tokens than raw-history prompting while preserving controlling definitions and boundaries at an equal or higher rate.

This is a testable hypothesis, not an established result.

---

## Secondary Hypotheses

1. Canonical reference resolution will reduce repeated restatement of definitions.
2. Selective clause retrieval will reduce irrelevant context.
3. Locked source resolution will reduce generic reinterpretation.
4. Source-bound retrieval will improve transfer across replaceable models and APIs.
5. Evaluation gates will identify failures that token reduction alone cannot detect.
6. The greatest savings will occur in long-running, definition-dense, boundary-sensitive systems.
7. The Source-line plus unresolved shorthand will not produce reliable savings or preservation.
8. Retrieval systems without source enforcement may improve efficiency while still permitting semantic drift.

---

## Falsification Direction

Evidence against the primary hypothesis would include conditions in which the proposed source-bound approach:

- does not reduce repeated input-token use relative to the relevant baseline;
- preserves definitions or boundaries less reliably than the baseline;
- produces apparent efficiency only by omitting required information;
- introduces source, provenance, non-merge, or non-substitution failures; or
- requires correction behavior that erases the apparent efficiency gain.

---

## Claim Status

No hypothesis on this page should be reported as a completed empirical finding until the corresponding controlled evaluation has been run and the evidence is published.
