# Three-Tier Criticality

The framework classifies AI-augmented applications by the consequence of a cognitive error:

- **Tier 1 — safety-critical.** An error could reach a safety consequence. The Command Broker architecture is required.
- **Tier 2 — quality-of-service.** An error degrades service or quality. Lighter qualification, but the broker discipline still applies.
- **Tier 3 — administrative.** No process or safety consequence.

Tier is an **application-level** judgment: it fixes whether the broker architecture is required at all. The [Bright Line](bright-line.md) is then drawn **action by action** within a governed application. A single Tier 1 application routinely contains both actions that must pass through the broker and lower-consequence actions that may execute under a lighter confirmation.
