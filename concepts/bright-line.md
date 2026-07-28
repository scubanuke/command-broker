# The Bright Line

> Above the Bright Line, an AI system may **analyze, synthesize, and recommend — but it may not command.**

Every action affecting the controlled process must pass through a human decision-maker — the **Command Broker** — who evaluates the AI's recommendation and authorizes or rejects it. The protection is **architectural, not procedural**: it depends on the physical separation between the AI's recommendation and the control action, so the AI cannot directly change a setpoint, valve, or breaker without affirmative human authorization.

Placement is **action by action**. Tier classification decides whether the broker architecture is required for an application at all; the Bright Line itself is then drawn against the consequence each individual action could produce. The same product can sit below the line for one action and above it for another.

See also: [Three-Tier Criticality](three-tier.md) · [Mechanism vs. Accountability](mechanism-accountability.md) · [The Proposer–Gate Pattern](proposer-gate.md).
