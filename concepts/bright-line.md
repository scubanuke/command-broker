# The Bright Line

> Above the Bright Line, an AI system may **analyze, synthesize, and recommend — but it may not command.**

Every **above-line** action — every action whose incorrect performance could produce a consequence at or above the facility's severity threshold — must be authorized by a qualified human, the **Command Broker**, who evaluates it on the merits and authorizes or rejects it. Below-line actions do not need that authorization. The protection is **architectural, not procedural**: the control system is incapable of executing an above-line action from an in-scope component without it.

The line is drawn on **consequence** — not on the technology that produced the action, and not on the architecture. The seam between the advisory layer and the command layer is a useful place to build the enforcement; it is not the line. A single gate placed at the seam leaves above-line actions on the advisory side ungated, and gates below-line actions on the command side for nothing.

Placement is **action by action**. One action is one change the output would make, if executed or acted upon — to a process parameter; to a protective function's settings, logic, bypass state or actuation criteria; or to the pre-authorized envelope or the gatekeeper. A recommendation and its acceptance are one action, and an action may not be split finer than the change it makes to lower its placement. The same product can sit below the line for one action and above it for another. Output that makes no change of its own — a summary, a display — is below the line, and carries the [indication-integrity](indication-integrity.md) obligation instead.

**The band is not the line.** An application's [criticality band](three-tier.md) sets how rigorous its assessment, qualification and audit must be. It does not decide whether the Command Broker obligation applies, and it does not decide placement. A Highest-band application contains below-line actions; a Lowest-band application may contain above-line ones.

**Scope is the carve-out.** The obligation reaches every component that does not meet the determinism carve-out: deterministic within a stated input bound *and* formally testable as deployed. Generative AI is the principal case, not the definition — a deterministic model never formally tested is in scope too. The carve-out is not a grant of autonomy, and it is not a finding that a component's actions are below the line.

The definition is fixed by **FD-BL** (the Foundational Definition — The Bright Line), and scope by **FD-LD**, as issued in the October 2026 Edition of the Foundational Definitions. *How* the required authorization is discharged, *how* the picture it rests on is trusted, and *how* "envelope" is used are settled by the determinations — [Advance Discharge](advance-discharge.md) (FD-BL-D1), [Indication Integrity](indication-integrity.md) (FD-BL-D2), and [Envelope](envelope.md) (FD-EV).

See also: [Criticality Bands](three-tier.md) · [Mechanism vs. Accountability](mechanism-accountability.md) · [The Proposer–Gate Pattern](proposer-gate.md) · [Advance Discharge](advance-discharge.md) · [Indication Integrity](indication-integrity.md) · [Envelope](envelope.md).
