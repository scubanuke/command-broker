# For Vendors &amp; Suppliers

You are supplying a generative-AI-enabled product into a setting governed by the Command Broker framework. Your product does not decide; it recommends, and a qualified human at the asset owner/operator (AOO) authorizes or rejects. This track walks the engagement from your side.

## What you own

- **The enforcement mechanism** and the **confirmation interface** — the architectural separation between recommendation and action.
- **The exercise mode** that injects known-erroneous recommendations so the AOO's brokers can be qualified against them.
- **The audit records**, structured so the AOO can reconstruct any brokered decision without your help.
- **Model-update notification** — advance notice of model, fine-tuning, and retrieval-source changes.

## What you cannot claim

A product characterization — "turnkey autonomy," "operator-free optimization" — **does not substitute for gate evidence and closes no gate**. See **[Mechanism vs. Accountability](../concepts/mechanism-accountability.md)**.

## Walk the journey (your side)

The Lens is set to **Vendor**. Read the six gates in order:

1. [Procurement](../journey/1-procurement.md)
2. [Factory Acceptance](../journey/2-factory-acceptance.md)
3. [Site Acceptance](../journey/3-site-acceptance.md)
4. [Operational Qualification](../journey/4-operational-qualification.md)
5. [Model-Update Re-Qualification](../journey/5-model-update-requalification.md)
6. [Periodic Drill](../journey/6-periodic-drill.md)

## Know the buyer's team

The engineer you demo to is not the buyer. On the AOO side the request is prepared by a working team — legal, corporate IT, and the plant's OT and systems engineers — and carried by a business lead up to an executive who must defend it to a CFO, a General Counsel, and the operational leadership of each site. Your materials have to survive being carried upward by someone non-technical into a finance-and-legal room. Equip your champion to sell up — a funding story the CFO can accept, a risk posture the GC can sign, an operational assurance the site VPs can trust — or the deal dies two levels above the engineer who liked it. The full treatment is in the standalone *Vendor Product-Readiness Guide*.

## Product-readiness checklist

A gate-by-gate checklist of what your product must demonstrate or deliver to pass each gate. Tailor per opportunity. Issued in full as the *Vendor Product-Readiness Guide*, Appendix A.

**Procurement**

- [ ] A tier-design statement and the configuration path to deploy at a different tier.
- [ ] Acceptance of no-training-on-customer-data, on-premises deployment, CIP-013 terms, and Part 21 reach.
- [ ] Disclosure of the underlying foundation model and provider, with change and re-qualification rights.
- [ ] No autonomy claim that substitutes for gate evidence.

**Factory Acceptance (FAT)**

- [ ] An action-by-action demonstration of Bright-Line placement.
- [ ] A working exercise mode that injects known-erroneous recommendations, with results recorded.

**Site Acceptance (SAT)**

- [ ] A confirmation interface with staleness and degraded-data flags and an override procedure.
- [ ] An audit record the AOO can reconstruct without your cooperation, retained independently of your systems.

**Operational Qualification**

- [ ] Delivery of the product-specific joint training event for the AOO's brokers.
- [ ] Support for AOO-defined role-based access and separation of duties.

**Model-Update Re-Qualification**

- [ ] Advance notification of model, fine-tuning, and retrieval-source changes.
- [ ] Support for broker re-qualification and audit continuity across changes.

**Periodic Drill**

- [ ] Support for the exercise mode and degraded-data behaviors the AOO's drills rely on.

**Cross-cutting**

- [ ] On-premises option; read-only with no write path; identity and access integration.
- [ ] No training on customer data, with residency controls.
- [ ] A liability line that warrants the mechanism even as it disclaims the advice.

## Worked example

See **CB-UC-1 — the BA Integrated Interface**, the vendor-facing confirmation-interface specification, in **[The Corpus](../corpus.md)**.
