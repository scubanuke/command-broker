# Gate 3 · Site Acceptance / Commissioning (SAT)

**Entry.** Product installed in the target operating environment. **Activities.** On-site verification of the confirmation gesture sequence, the staleness / degraded-data flags, and the override procedure (CB-UC-1 §§4–5); and verification that the AOO can independently reconstruct a brokered decision from the audit record **without vendor cooperation** (DBA-VC §3.7). **Exit.** A SAT record plus a passing audit-reconstruction test. **Accountable.** The AOO.

<div class="lens lens-aoo">

<p class="lenstag">Asset Owner / Operator</p>

**You do.** Run the audit-reconstruction test yourself. If you cannot reconstruct a brokered decision from the record without the vendor's help, the gate does not close. Verify the confirmation gesture, the staleness flags, and the override against your operating limits.

</div>

<div class="lens lens-vendor">

<p class="lenstag">Vendor / Supplier</p>

**You deliver.** The confirmation interface, the staleness / degraded-data flags, and the override procedure. You support — but do not perform — the AOO's reconstruction test. The audit record must be readable independently of your systems.

</div>
