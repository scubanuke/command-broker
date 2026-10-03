# Indication Integrity

> An authorization is only as good as the picture it rests on. **FD-BL-D2** requires that the state a broker — or a [gatekeeper](advance-discharge.md) — authorizes against be *real*.

Output of an in-scope component that makes no change of its own — a synthesis that changes no setpoint — is below the [Bright Line](bright-line.md) as an action, and the authorizations it grounds do not move it above the line. They attach an obligation to it instead. An operator who confirms an above-line action against a corrupted or drifted synthesis is not blind; he is **confident and wrong**, and the human authorization the framework relies on has been hollowed out with no fault registered.

FD-BL-D2 closes that hole with a qualifier — not a placement change — that attaches to any output of an in-scope component that can function as the basis for an above-line authorization, or as an input on which placement or discharge depends, such as the plant state the consequence classifier routes on.

- **I1 — attaches by function.** Whatever the output's own placement, if it can ground an above-line authorization, or feed placement or discharge, it carries the obligation; if it cannot, it does not.
- **I2 — traceable to independently verifiable values.** The output must be anchored to values confirmable through a path *independent of failure* from the component that produced it — a direct measurement, a diverse instrument, a deterministic channel.
- **I3 — not the sole basis.** There must be an independent path to confirm the state; a single synthesis may not carry an above-line authorization alone. Where no such path exists, the authorization is unavailable on that basis.

Governed by **FD-BL-D2**, the determination under [FD-BL](bright-line.md) resolving its §6.2. It binds both the human-broker case and the verified-gatekeeper case under one rule, and it settles the interim input-integrity floor that [Advance Discharge](advance-discharge.md) had held open.
