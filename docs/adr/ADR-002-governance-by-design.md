# ADR-002: Governance-by-Design over Post-Hoc Governance

## Status
Accepted

## Context
In regulated environments, governance is often applied after data pipelines are built, leading to:
- rework and compliance gaps
- inconsistent data handling
- lack of auditability

## Decision
Embed governance controls directly into the platform architecture across all layers rather than applying governance as a downstream process.

## Rationale
- ensures consistent enforcement of policies
- reduces rework and compliance risk
- supports auditability and traceability
- aligns with scalable platform design

## Consequences

### Positive
- improved data trust and consistency
- reduced downstream rework
- stronger compliance posture

### Tradeoffs
- requires upfront design investment
- adds complexity to platform design

### Negative
- slower initial onboarding if patterns are not well-defined
