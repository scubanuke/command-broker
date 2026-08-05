# Advance Discharge

> The Command Broker authorizes *in the moment*. **FD-BL-D1** settles a narrow exception: for a bounded class of above-line actions, the authorization may be discharged **in advance** — by a verified deterministic gatekeeper, not by a human at the instant.

The [Bright Line](bright-line.md) requires substantive human authorization for an above-line action. FD-BL-D1 asks *how* that authorization may be supplied, and answers: advance discharge is permitted **only** where the whole safety case lives in a formally verified **gatekeeper** the generative proposer can neither modify nor bypass, under three conditions.

- **R1 — the gatekeeper holds the safety case.** The proposer holds *proposal authority only*; the gatekeeper holds *veto authority* and is the sole path to the process. The proposer's non-determinism cannot cause an unsafe action, because every action it proposes is disposed of by a component that carries the safety case.
- **R2 — completeness over state, trajectory, and rate.** The gatekeeper's acceptance set is *proven* safe — not a range check — so that no admissible sequence of individually acceptable actions can ratchet the process into an unsafe path. This is what bounds *selection*, not only admissibility.
- **R3 — envelope changes are excluded.** A change *to* the [pre-authorized envelope](envelope.md) itself — or to the gatekeeper's limits or logic — routes to in-the-moment authorization or offline requalification, never advance discharge. No live in-field learning of the gatekeeper.

Where the R2 proof cannot be produced, or R3 applies, the action takes **in-the-moment** Command Broker authorization, unchanged.

**Two objects, in series.** A *consequence classifier* answers placement (per action, above or below); a *gatekeeper* answers discharge (for above-line actions inside a valid envelope). They are distinct, they are not merged, and both appear in the evidentiary record — this is the [Proposer–Gate Pattern](proposer-gate.md) made normative.

Governed by **FD-BL-D1**, the determination under [FD-BL](bright-line.md) resolving its §6.1. Nothing here reclassifies an action or lowers the line; it changes only *how* the required authorization is supplied.
