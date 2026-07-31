# Criticality Bands

The framework places each AI-augmented application in a **criticality band** — set by the worst credible consequence of a cognitive error in it (take-the-max across consequence categories):

- **Highest.** A worst-credible error could reach a safety-critical or otherwise catastrophic consequence. The Command Broker architecture is required.
- **Mid.** An error produces significant but bounded harm — degraded service, quality, or reliability. Lighter qualification, but the broker discipline still applies.
- **Lowest.** No process, safety, or reliability consequence.

The band is an **application-level** judgment: it fixes whether the broker architecture is required at all. The [Bright Line](bright-line.md) is then drawn **action by action** within a governed application. A single Highest-band application routinely contains both actions that must pass through the broker and lower-consequence actions that may execute under a lighter confirmation.

The band answers *how much is at stake*. A separate, orthogonal axis — the **error class** (safety-critical, quality-of-service, compliance) — answers *what kind* of cognitive error the assessment tests for; it is carried by the Tiered Assessment Framework, not fixed by this determination.
