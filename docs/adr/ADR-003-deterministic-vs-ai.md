# ADR-003: Separation of Deterministic Logic and AI-Assisted Behavior

## Status
Accepted

## Context
AI and retrieval-based systems introduce non-deterministic behavior, which can create risk in regulated environments if not properly controlled.

At the same time, deterministic logic is required for:
- compliance enforcement
- repeatable data transformations
- auditable decision-making

## Decision
Maintain a clear separation between deterministic platform logic and AI-assisted behavior, with governance controls applied to both.

## Rationale
- ensures core platform behavior remains predictable and auditable
- allows AI to augment, not replace, controlled workflows
- reduces risk of untraceable or non-compliant outputs

## Consequences

### Positive
- improved explainability and auditability
- safer integration of AI capabilities
- clearer control boundaries

### Tradeoffs
- requires dual design patterns (deterministic + AI-assisted)
- additional governance required for AI interactions

### Negative
- increased architectural complexity
