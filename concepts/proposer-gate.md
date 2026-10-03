# The Proposer–Gate Pattern

The shape of every governed interaction: **the AI proposes; the Command Broker authorizes; the Gate holds every above-line action until it is authorized.**

The AI surfaces a recommendation with its supporting data — the readings, the pattern it matched, its confidence, and the potential consequence. Only then does the human broker authorize the action through the conventional control interface. A **verified deterministic component** — an interlock, a Technical-Specification limit, an LCO check — may serve as part of the enforcement, because its behavior can be exhaustively checked in a way a generative model's cannot.

The pattern is what the [Bright Line](bright-line.md) looks like in operation, and it is enforced coarsely by [role-based access](../journey/4-operational-qualification.md) — who reaches which capability — and finely by the Gate — the enforcement interlock that holds a specific above-line action until it is authorized. The Gate never authorizes and never stands in for the Broker.

This pattern is made **normative** by [FD-BL-D1](advance-discharge.md): the deterministic component is a formally verified **gatekeeper**, which admits actions under a pre-authorized envelope the Command Broker authorized in advance, and which carries the whole safety case (R1), proven complete over state, trajectory, and rate (R2), with changes to its [pre-authorized envelope](envelope.md) excluded from advance discharge (R3). The classifier and the gatekeeper are **two objects in series** — the classifier answers placement, the gatekeeper answers discharge — and both appear in the evidentiary record. See [Advance Discharge](advance-discharge.md).

The pattern's name is older than the vocabulary. In *Proposer–Gate*, "Gate" means the verified gatekeeper, which the Foundational Definitions now distinguish from the Gate, the enforcement interlock. The human discharges; the gatekeeper admits.
