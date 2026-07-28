# For Asset Owner/Operators

You are acquiring a generative-AI tool and putting it into service where a wrong answer can reach consequence. The Command Broker framework says a qualified human — yours — must sit between the tool's recommendation and the action. This track walks the engagement from your side.

## What you own

- **The human broker.** Accountability for the brokered decision is yours and never flows to the vendor. See **[Mechanism vs. Accountability](../concepts/mechanism-accountability.md)**.
- **Qualification.** You staff, qualify, and maintain the brokers against the CB-IB standard, and re-qualify them when the product materially changes.
- **Audit reconstruction.** You must be able to reconstruct any brokered decision from the record *without vendor cooperation*.
- **Role definition.** Your IT and OT process engineers jointly define the tool's roles — IT provides its home, OT its data and process semantics.
- **The funding case.** The substrate the tool rides on is capitalized by your compliance obligation. See **[Compliance as Anchor Tenant](../concepts/anchor-tenant.md)**.

## Walk the journey (your side)

The Lens is set to **AOO**. Read the six gates in order:

1. [Procurement](../journey/1-procurement.md)
2. [Factory Acceptance](../journey/2-factory-acceptance.md)
3. [Site Acceptance](../journey/3-site-acceptance.md)
4. [Operational Qualification](../journey/4-operational-qualification.md)
5. [Model-Update Re-Qualification](../journey/5-model-update-requalification.md)
6. [Periodic Drill](../journey/6-periodic-drill.md)

## It's a team effort on the AOO side

The AOO is not a person. Behind the business lead stand three working functions — **Legal**, **CorpCo IT**, and **OT / systems engineering** (engineering isn't a fourth chair; SE and OT wear that hat) — and the request escalates through the business lead to an executive who must defend it to the **site VPs**, the **CFO**, and the **General Counsel**. Because the technical team may not be in the room, the request must be self-standing in three cuts: a funding story for the CFO (the [anchor-tenant](../concepts/anchor-tenant.md) argument), a risk posture for the GC (the terms and conditions in the checklist below), and an operational assurance for the site VPs (read-only, no write path, validated per unit). The full treatment is in the standalone *AOO Acquisition Guide*.

## What to ask your vendor

A gate-by-gate checklist for the acquisition team — questions to put to a vendor and evidence to require. Tailor per acquisition. Issued in full as the *AOO Acquisition Guide*, Appendix A.

**Procurement**

- [ ] What tier do you assign the intended application, and what configuration changes deploy it at a different tier?
- [ ] Will you contractually commit not to train your models on our data, and support on-premises deployment?
- [ ] Will you accept NERC CIP-013 supply-chain terms and the reach of 10 CFR Part 21 defect reporting?
- [ ] Will you disclose the underlying foundation model and its provider, and grant re-qualification or exit rights if it changes?
- [ ] Does your product characterization avoid claiming autonomy that would substitute for gate evidence?

**Factory Acceptance (FAT)**

- [ ] Will you demonstrate the product's Bright-Line placement action by action?
- [ ] Will you run the exercise mode that injects known-erroneous recommendations, and record the results?

**Site Acceptance (SAT)**

- [ ] Can we independently reconstruct any brokered decision from the audit record without your cooperation?
- [ ] Will you verify the confirmation gesture, staleness and degraded-data flags, and the override against our operating limits?
- [ ] Is the audit record readable and retained independently of your systems?

**Operational Qualification**

- [ ] Will you deliver the product-specific joint training event for our brokers?
- [ ] Does the tool support the role-based access we define, bound to competency records, enforcing separation of duties and approver independence?

**Model-Update Re-Qualification**

- [ ] Will you notify us in advance of model, fine-tuning, and retrieval-source changes?
- [ ] Do we retain the right to re-qualify affected brokers before the updated product runs above the Bright Line, with audit continuity preserved?

**Periodic Drill**

- [ ] Will you support the exercise mode and degraded-data behaviors our drills rely on?

**Cross-cutting — Legal, IT, and OT/SE**

- [ ] Legal: no training on our data; audit, exit, escrow, and certified-deletion rights; the liability line (no warranty on advice, full warranty on mechanism); CIP-013, Part 21, and export flow-down.
- [ ] IT: on-premises option; identity and access integration; read-only with no write path to control systems; configuration-controlled updates; independent logging.
- [ ] OT/SE: calibration to each unit's as-built, as-operated state; a no-write separation you can see; Technical Specification and LCO safety; commercial-grade-dedication support.

## Worked example

See the **[Nuclear SE Support AI](../examples/nuclear.md)** — one tool used by system engineering, maintenance, and operations, with four broker seams governed as role-based access.
