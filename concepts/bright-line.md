# The Bright Line

> Above the Bright Line, an AI system may **analyze, synthesize, and recommend — but it may not command.**

Every action affecting the controlled process must pass through a human decision-maker — the **Command Broker** — who evaluates the AI's recommendation and authorizes or rejects it. The protection is **architectural, not procedural**: it depends on the physical separation between the AI's recommendation and the control action, so the AI cannot directly change a setpoint, valve, or breaker without affirmative human authorization.

Placement is **action by action**. Band classification decides whether the broker architecture is required for an application at all; the Bright Line itself is then drawn against the consequence each individual action could produce. The same product can sit below the line for one action and above it for another.

The definition is fixed by **FD-BL** (the Foundational Definition — The Bright Line). *How* the required authorization is discharged, *how* the picture it rests on is trusted, and *how* "envelope" is used are settled by the determinations — [Advance Discharge](advance-discharge.md) (FD-BL-D1), [Indication Integrity](indication-integrity.md) (FD-BL-D2), and [Envelope](envelope.md) (FD-EV).

See also: [Criticality Bands](three-tier.md) · [Mechanism vs. Accountability](mechanism-accountability.md) · [The Proposer–Gate Pattern](proposer-gate.md) · [Advance Discharge](advance-discharge.md) · [Indication Integrity](indication-integrity.md) · [Envelope](envelope.md).
