# Claim Boundaries | Source-Line Compression and Token Efficiency

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author:** Alyssa Solen

---

## Status Boundary

The proposed efficiency gain has **not** been experimentally established by this repository.

This repository defines a construct, architecture, research hypothesis, and measurement design.

Any future result must be reported from the actual controlled evaluation rather than inferred from the proposal.

---

## This Repository Does Not Claim

This repository does **not** claim that:

- the literal Source-line contains the full Canon inside its text;
- a model will understand canonical terms correctly without access to the Canon;
- short labels alone are lossless compression;
- retrieval is token-free;
- all long context can be eliminated;
- model attention is perfectly preserved as context grows;
- source resolution guarantees correct output without evaluation;
- semantic equivalence can be assumed without testing;
- provider caching and internal serving costs are fully visible; or
- the proposed efficiency gain has already been experimentally established.

---

## Required Measurement Separation

Measured results must distinguish:

- token reduction;
- cost reduction;
- latency reduction;
- definition preservation;
- behavioral preservation; and
- provenance preservation.

These dimensions may not be collapsed into a single efficiency claim.

---

## Failure Boundary

Efficiency may not be achieved by:

- detaching a term from its Source-line;
- weakening its canonical definition;
- substituting authorship or source;
- allowing unsupported generic reinterpretation;
- omitting required boundary information; or
- hiding hard preservation failures inside an aggregate efficiency score.

A smaller prompt that changes the controlling meaning is not successful compression.

A lower token count that loses source, boundary, or provenance is not a pass under this framework.

---

## Evidence Rule

The architecture and hypotheses identify what should be tested.

Only completed runs and preserved evidence can establish whether the proposed mechanism succeeds, partially succeeds, fails, or remains unsupported.
