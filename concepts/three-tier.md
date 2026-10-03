# Criticality Bands

The framework places each AI-augmented application in a **criticality band** — set by the worst credible consequence of a cognitive error in it (take-the-max across consequence categories):

- **Highest.** A worst-credible error could reach a safety-critical or otherwise catastrophic consequence. The most rigorous assessment, qualification and audit apply.
- **Mid.** An error produces significant but bounded harm — degraded service, quality, or reliability. Assessment, qualification and audit are proportionate to it.
- **Lowest.** No reach to a critical function, life-safety, or a critical service. The lightest regime applies.

The band is an **application-level** judgment: it sets the rigor of assessment, qualification and audit. It does **not** decide whether the Command Broker obligation applies — scope is the determinism carve-out (FD-LD) — and it does not decide placement. The [Bright Line](bright-line.md) is drawn **action by action**, on consequence, in every band. A Highest-band application routinely contains below-line actions that need no Broker authorization; a Lowest-band application may contain above-line actions, and each of those needs it.

The band answers *how much is at stake*. A separate, orthogonal axis — the **tier** (safety-critical, quality-of-service, compliance-driven) — answers *what kind* of cognitive error the assessment tests for; it is carried by the Tiered Assessment Framework. *Tier* names the error axis and *criticality band* the application axis, and neither is inferred from the other.
