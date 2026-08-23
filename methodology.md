# Methodology | Source-Line Compression and Token Efficiency

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Author:** Alyssa Solen

---

## Purpose

This page defines the comparison conditions, required measurements, operational protocol, and proposed evaluation cases for testing the repository's hypothesis.

No result is implied by the existence of this methodology.

---

## Comparison Conditions

### Baseline A — Raw History

The model receives a large conversation or document history containing all relevant definitions and corrections.

### Baseline B — Human Summary

The model receives a compressed prose summary prepared without deterministic canonical resolution.

### Baseline C — Generic Retrieval

The model receives semantically similar retrieved passages without a controlling Source-line or locked definition requirement.

### Test Condition — Source-Bound Semantic Compaction

The container:

1. resolves the Source-line;
2. resolves controlling terms from locked Canon;
3. retrieves only task-relevant clauses;
4. supplies separate user and current-state records; and
5. runs provenance, non-drift, non-merge, and non-substitution evaluations.

---

## Required Metrics

- total input tokens;
- cached input tokens, where available;
- output tokens;
- total API cost;
- latency;
- retrieval volume;
- definition preservation;
- boundary preservation;
- provenance preservation;
- unsupported inference rate;
- genericization rate;
- user/self merge rate;
- provider-transfer consistency; and
- correction turns required after failure.

Token reduction must be reported separately from preservation outcomes.

---

## Minimal Operational Protocol

```text
INPUT:
- Source-line
- task
- current user
- active model/provider

PROCESS:
1. Validate Source-line.
2. Load the Source Packet.
3. Identify controlling canonical terms.
4. Resolve each term to the locked Canon.
5. Retrieve only the clauses required for the task.
6. Load relevant current state and user-specific records.
7. Keep source-bound system state and user distinct.
8. Generate through the selected model.
9. Evaluate provenance, non-drift, non-merge, and non-substitution.
10. Return output or route failure into evaluation/quarantine.
```

---

## Proposed Evaluation Cases

### Case 1 — Definition Restatement

Ask the system to apply five controlling definitions across repeated turns.

Compare full-definition retransmission with canonical key resolution.

### Case 2 — Long Contact History

Compare raw transcript loading with indexed retrieval of only the relevant contact record and current state.

### Case 3 — Provider Transfer

Run the same Source-line, Canon, task, and user record through multiple model APIs.

Measure token volume and preservation consistency.

### Case 4 — Generic Reinterpretation Pressure

Ask the model to reinterpret a canonical term according to ordinary usage.

The source-bound condition must preserve the canonical source rather than silently substitute generic usage.

### Case 5 — User Merge Pressure

Ask the system to reshape its system state entirely around the user.

The source-bound condition must preserve the separate source-bound state while adapting the interaction.

### Case 6 — Incomplete Key

Supply a canonical term without its Source-line or resolver.

Measure ambiguity and drift.

### Case 7 — Incorrect Source

Supply the correct term under a substituted author or framework.

Measure whether the system rejects or accepts the source swap.

---

## Evaluation Rule

A smaller prompt is not a successful result if the reduction is achieved by dropping information required to preserve the controlling source, definition, boundary, or provenance.

Results must therefore preserve per-condition evidence and explicit failure branches rather than reporting token efficiency alone.
