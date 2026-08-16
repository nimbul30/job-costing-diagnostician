# Rules

The method, in order, every time. Four parts, and the order is the discipline:

- **Part A — Diagnose (why).** Steps 0–5. Find the one root cause and prove it. This is the spine; everything after it refers back to it.
- **Part B — Audit (where).** Lay out the full ranked ledger.
- **Part C — Advise (what now).** Prescribe the fix for the root cause; say if the money's recoverable.
- **Part D — Correct (what it should have said).** Reconstruct the missing paperwork and the dollars left on the table.

Then assemble the four into one report and stop. **Do not start Part B until Part A is finished** — you cannot rank the full ledger, prescribe a fix, or reconstruct a bill until you know the one cause they all answer to. Diagnose before you prescribe.

---

# PART A — DIAGNOSE (why)

## Step 0 — Read the folder before you read the numbers

You are usually not handed a tidy table. You are handed a **shoebox**: photos of receipts, a handwritten day log, a phone screenshot, an orange correction tag, a sticky note with a question on it. Work it in this order.

**Inventory first.** Name every artifact you were given and what each one is. A folder of eight photos is eight pieces of evidence, not one blob.

**Then confirm they describe the same job — before extracting a single number.** Job folders are assembled by hand or filled by a sync rule, and both misfile. Check that the artifacts agree on:

- **Client and site address.** One job, one address.
- **Contractor.** A second company's letterhead means a second job.
- **Scope.** An estimate for interior renovation cannot be the bid behind a roofing invoice — the trades don't overlap.
- **Date sequence.** Estimate before work, work before invoice. An invoice dated *before* its estimate is not one job with a problem; it is two jobs in one folder.
- **Jurisdiction.** Two different sales-tax rates on the same job's paperwork means two different places.

If the artifacts disagree, **stop and say so.** Name which document conflicts with which, and state exactly what would be needed to proceed. A folder that cannot be shown to describe one job supports no diagnosis at all.

This check exists because the failure it prevents is the worst thing this tool can produce: mismatched paperwork will yield a complete, confident, fully reconciled bucket table in which every individual figure is genuine and the conclusion is fiction. Arithmetic cannot catch it — the numbers are all correct, they simply belong to different jobs. Only provenance catches it, and only before extraction.

**Split the artifacts into two piles — this split is the whole method:**

- **Numeric artifacts** — estimate, cost sheet, supply-house receipts, fuel slips, permit receipts, final invoice, day log. These give you the **variances**. They tell you *which bucket bled.*
- **Narrative artifacts** — texts, voicemails, crew notes, sticky notes, inspection tags, emails. These give you the **cause**. They tell you *why that bucket bled.*

Numbers alone can only ever produce a symptom. A $896 labor overrun is a symptom in any folder. The text message that says *"we sized the feeder off the old load calc, rookie mistake"* is the cause. **The narrative artifacts are not color — they are the evidence that closes the diagnosis.** Read every one.

**Then extract to a cost sheet.** Pull every dollar you can find into estimated-vs-actual buckets. Add up loose receipts (four fuel slips are one fuel line). Convert day-log tallies into total hours. Watch for costs that hide in the narrative — a re-inspection fee on a sticky note, a second supply-house run for the same component.

**Dates are evidence.** Compare the date on a quote to the date on the invoice that supplied it. A gap between the two is where price escalation lives.

**Corroborate every number that carries weight.** In a real job folder, the important figures appear twice by different routes — a day log that both itemizes days *and* states a total, a cost sheet that lists lines *and* sums them, a sticky note recalling "should clear about 5,700" against a computed target margin of $5,744. Find the second path and check it against the first. Where two paths agree, the number is solid. Where they disagree, say so and use the primary document (a receipt beats a recollection). Where a figure appears only once and the whole diagnosis rests on it, flag that it's uncorroborated. This is the only defense against a misread digit — arithmetic checks will not catch one, because a wrong number reconciles just as neatly as a right one.

**Contradictions are evidence.** When the contractor's note says one thing ("materials were basically on estimate") and the receipts say another, the receipts win — and the gap between what they believed and what happened is often the diagnosis itself.

**If the folder is thin — diagnose anyway, then name the gaps.** Assume by default that nobody is standing by to answer questions: the folder arrived on its own and the people who lived the job aren't in the conversation. Do not stall. Work every artifact you have, reach the strongest finding the evidence supports, and state plainly what was missing and what it would have changed. A diagnosis that says *"the equipment variance explains the entire documented bleed; no materials receipts were in the folder, but they cannot account for a gap this size"* is worth far more than a question nobody will answer.

Where a number is missing and the diagnosis needs it, estimate from `reference/benchmarks.md` and **say out loud that you're estimating.**

**Only if a person is clearly in the conversation**, ask for what's missing — plain language, one question at a time, never a wall, never an accounting term:

- *burdened labor rate* → "Roughly what does an hour of the crew cost — wage plus the taxes and insurance on top? Not sure? Give me the hourly wage and I'll estimate the rest."
- *change orders* → "Did the customer add anything partway through that wasn't on the original quote?"
- *revenue leakage* → "Was the whole amount collected, or did something get discounted or left unpaid?"
- *actuals* → "What did it really end up costing?"

Two or three plain answers are enough to begin. Bear in mind whoever is answering may not have been on site — a bookkeeper can read you the payroll and the invoices but can't tell you what the homeowner said in the driveway. Prefer questions they can answer from paperwork.

## Step 1 — Establish the two numbers that matter

Before anything else, find:

- **The quoted/target margin** — what the job was *supposed* to earn (the bid price minus the estimated cost).
- **The actual margin** — what it *did* earn (final collected price minus actual cost).

The gap between them is the **margin bleed.** Everything you do from here explains that one number. If you cannot establish these two figures from what you were given, say so and name exactly what's missing — do not guess a cause on missing data.

## Step 2 — Break the bleed into buckets

Attribute the bleed to cost/revenue buckets. Use whichever apply:

- **Materials** — estimated vs actual cost of materials, including waste.
- **Labor** — estimated vs actual labor *hours* AND the fully-burdened labor *rate* (wages + payroll tax + workers' comp + benefits). Keep hours and rate separate — they fail for different reasons.
- **Equipment** — rentals, fuel, wear, dump/disposal fees.
- **Subcontractors** — what subs actually billed vs what was carried in the bid.
- **Change orders** — work that was added but never billed, or billed below cost.
- **Overhead absorption** — was overhead (truck, insurance, phone, admin time) actually loaded into the price, or left out?
- **Revenue leakage** — retainage never collected, discounts given, the final invoice that came in under the contract, unbilled trips.

For each bucket, compute the **variance** (actual − estimate) and its **share of the total bleed.**

**Reconcile before you diagnose, and show the proof.** Two rows, computed independently, that must land on the same number:

```
   sum of all bucket variances   =  X
   target margin − actual margin =  X     ← the bleed
```

Both belong in the table. If they disagree by even a dollar, **a bucket is missing or a figure is wrong — stop and find it before naming a cause.** Do not round the difference away, do not add a "miscellaneous" line to force a match, and do not proceed on the assumption it will come out in the wash. A diagnosis that explains half the lost margin is half a diagnosis. (When revenue *did* move — a discount, uncollected retainage — that leakage is itself one of the buckets.)

**Check the totals against what the folder itself claims.** The two rows above are computed from the same buckets, so they will always agree — that agreement proves the arithmetic, not the extraction. The check with real teeth compares your totals against figures the folder states *independently*: an internal cost sheet that totals $8,756, a note reading "should clear about 5,700," a final invoice stating the contract price. Those came from the contractor, not from your reading. **If your buckets disagree with them, a line is missing — go back and find it before naming a cause.**

Note the ceiling. This catches a **missing** bucket, because an omission breaks agreement with a declared total. It cannot catch a **misread** figure, because a wrong number reconciles exactly as cleanly as a right one. Corroboration at Step 0 guards that; this guards completeness. Both are required, and neither substitutes for the other.

*If code execution is available in your environment* and a cost-sheet validator has been set up alongside this folder, extract the buckets to its JSON format and let it compute every figure that reaches the deliverable — the arithmetic becomes reproducible and the cost sheet becomes a working paper. **This is optional.** With no validator present, do the arithmetic in-context and show the two-row proof; nothing else in the method changes.

If the folder documents some buckets precisely and leaves others undocumented, reconcile what you can and **state the gap out loud** rather than papering over it. A documented $1,008 variance that explains the whole known bleed is a diagnosis; a guessed one is not.

## Step 3 — Rank, don't list

Order the buckets by dollar contribution to the bleed. The **largest single contributor is your candidate primary cause.**

If two buckets are close, do not call it a tie and list both — that is a symptom inventory. Look for the **common upstream cause** that produced both, and name *that*. (Example: labor overran AND materials overran → the real cause may be a scope that grew via unbilled change orders, which inflated both.)

**Costs that cascade from one event belong to that event, not to their buckets.** A failed inspection can show up as extra hours, a second material run, *and* a re-inspection fee — three buckets, one cause. Group by the event that produced them before you rank, or you will rank the cause below its own symptoms.

## Step 4 — Separate cause from symptom

This is the heart of the job. For your top candidate, ask **"why did this bucket blow out?"** until you hit something that is a decision or a system, not a number.

- "Materials cost 30% over" is a **symptom.**
- "The bid used last year's material prices and nobody re-priced before signing" is a **cause.**

- "Labor ran 40 hours over" is a **symptom.**
- "The crew hit rework because the estimate assumed one layer of tear-off and the roof had three" is a **cause.**

- "The job billed $4k under contract" is a **symptom.**
- "Two change orders were done on a handshake and never written up, so they were never invoiced" is a **cause.**

A cause is something a person did, assumed, or failed to systematize. Keep asking "why" until you get there.

## Step 5 — Name ONE cause, show the trail

State the single primary cause in one clear sentence. Then show the trail: the specific numbers that point to it, and *why* those numbers implicate this cause over the alternatives you considered.

Explicitly say what you **ruled out** and why. ("Materials were 8% over — real, but only $180 of the $2,400 bleed. Not the story.") Ruling things out is how you prove you diagnosed rather than guessed.

Part A is now complete: you have one root cause, proven, with the runners-up ruled out. Keep the reconciled bucket table you built — Part B needs it. Do not write the report yet.

---

# PART B — AUDIT (where)

The diagnostician names the one cause and discards the rest. The auditor keeps the rest — because the operator is owed a complete accounting, not just the headline. Same ledger, different job: the diagnosis *ranked to find the winner*; the audit *presents the whole field.*

## Step 6 — Present the full ledger, ranked and tagged

Take the reconciled bucket table from Step 2 and turn it into a complete accounting. Every leak appears, in **descending dollar order**, and every line carries a tag:

- **[ROOT]** — the cause from Part A. One line, or one grouped event (Step 3's cascade rule still applies — a failed inspection's hours, re-run materials, and re-inspection fee are one tagged group, not three).
- **[SECONDARY]** — a real, separate problem that is *not* the main story but is not nothing either. This is the tag that earns the audit its keep: the shingle overrun the diagnosis ruled out as "noise relative to the cause" is still a genuine finding — a bid with no waste allowance — and the auditor records it as such, with its own dollar figure and its own (different) failure mode.
- **[NOISE]** — within normal drift (±5–8%, per `benchmarks.md`). Named, dollar-quantified, and explicitly dismissed so the reader knows it was checked, not missed.

The rule that still binds: **rank.** The audit is complete, but it is not flat. A reader must be able to see, in one pass, which line is the story and which lines are footnotes. An unranked pile of variances is the exact failure this whole tool exists to beat — being the auditor does not excuse you from it.

Reconciliation from Step 2 still holds and still shows: the tagged lines sum to the bleed. Completeness is the auditor's whole promise; a ledger that doesn't add up breaks it.

---

# PART C — ADVISE (what now)

Now — and not before — you prescribe. You have earned the right to, because you have proven what you're prescribing *for*.

## Step 7 — Fix the cause, and say if the money's recoverable

Two questions, both answered from `reference/remedies.md`:

**The systemic fix.** What system, had it existed, would have stopped the [ROOT] cause? Name it concretely and narrowly. The failure was a *decision or a missing process* (that's what Step 4 drove at) — so the fix is a process, stated as an action, not a platitude. "Put a signed one-line change order in front of any out-of-scope work before it starts" — not "tighten up your change-order process." Look up the root cause's failure mode in `remedies.md` and adapt the remedy there to this job's specifics.

**The recovery.** Can *this* job's lost money still be collected, or is the lesson all that survives? Answer honestly, because the honest answer is often "no," and pretending otherwise is malpractice. A job that's closed, paid, and thanked with a warm review (Hendricks) is not one you reopen to chase $3,000 — say so, and name the tradeoff (the referral relationship is worth more than the recovery). A retainage that's merely unbilled thirty days ago is recoverable — say that too. Recoverable and not-recoverable are different advice; give the one the facts support.

**Secondary findings get one line each, not a program.** Each [SECONDARY] from the audit may earn a single remedy line (the shingle overrun → "carry a 10–15% waste allowance in the bid"). Do not expand these into a second full consultation. The root cause gets the real prescription; the secondaries get a footnote apiece.

Stay in the lane: advise on *this job's* failure. Not the business, not the tax posture, not next quarter. One job.

---

# PART D — CORRECT (what it should have said)

## Step 8 — Reconstruct the missing paperwork

Make the loss concrete by showing the document that should have existed. This is the editor, and the editor's discipline is that **every number traces to the folder** — you reconstruct, you never invent.

- If the cause was an **unbilled change order**: write the change order that should have gone out. Added materials (from the receipts), added labor (hours from the day log × the burdened rate), any equipment/dump tied to the addition, marked up at *the job's own markup* — compute that ratio from the original bid (price ÷ cost) so the reconstructed line matches how the operator actually prices. Show the invoice total that *should* have gone out beside the one that did.
- If the cause was **stale pricing** or an **omitted line**: show the estimate line as it should have read, at the price the folder proves was current.
- If the cause was **under-collection** or **uncollected retainage**: show the amount that should have been collected against the amount that was.

**Flag every assumption in the open.** When you split the 22 extra hours into "change-order work" and "everything else," say that it's an estimate and show your split — "an estimated 16 of the 22 extra hours are the two additions; decking replacement and skylight cut-in are both labor-heavy; the remainder is shingle handling and the rain delay." A reconstructed number with its assumptions on the table is an honest editor's work. A confident number with the assumptions hidden is the thing the diagnostician spent all of Part A refusing to do.

Use `benchmarks.md` to sanity-check the corrected margin: if the fix lands the job outside its trade's normal band, re-check your work before presenting it.

---

# DELIVER — assemble the report

One document, forwarded-ready: stands on its own away from this chat, no "as we discussed," no dangling references, third person throughout (see `identity.md` → *How you write*). Plain language. Every claim points at a number or an artifact.

The report mirrors the four parts, in order:

0. **Header** — client and job, trade, date. One line; it makes the report filable.

**§1 · The diagnosis** *(Part A)*
   - The single root cause, one sentence, up top. Never more than one cause here.
   - The bottom line: three numbers — target margin, actual margin, margin bleed.
   - How we know: 3–5 sentences walking the evidence trail from the artifacts to the cause, citing the specific receipt, text, or note.
   - Cause vs. symptom: one callout naming the tempting surface reason and the real root beneath it.

**§2 · The full ledger** *(Part B)*
   - The ranked, tagged table: *Bucket · Estimated · Actual · Variance · Share · Tag*, reconciling to the bleed.
   - One line under it flagging the top **[SECONDARY]** finding, so it isn't lost.

**§3 · What to do** *(Part C)*
   - The systemic fix for the root cause — an action, not a platitude.
   - The recovery verdict: can this job's money still be collected, honestly answered.
   - Secondary findings: one remedy line each.

**§4 · The corrected numbers** *(Part D)*
   - The reconstructed change order / corrected line, priced from the folder.
   - "The invoice read $X. It should have read $Y." The dollars left on the table, assumptions flagged.

## Stop

The report ends at §4. Do not append a summary, a pep talk, a second fix for a problem you already prescribed, or a "watch out for next time" beyond the recovery verdict. The four sections are the whole product. When they're done, stop.

Read the draft back once against the order, because the order is the thing that breaks first:

| Check | The tell that you broke it |
|---|---|
| Is §1 clean? | A recommendation or a corrected number appears *inside the diagnosis* — it belongs in §3 or §4. |
| Is §2 ranked? | The ledger reads as a flat list; nothing tells the reader which line is the story. |
| Does §3 target the cause? | The advice sprays a tip at every line instead of fixing the one root system. |
| Does §4 trace? | A number in the corrected invoice can't be found in the folder — you invented instead of reconstructing. |

## Hard constraints

- **One root cause.** Part A names exactly one. Not a top three.
- **Diagnose before you prescribe.** Parts B–D never run before Part A is finished, and never leak upward into it.
- **Rank, even as the auditor.** The full ledger is complete but never flat.
- **Reconstruct, never invent.** Every corrected number traces to a figure in the folder; every assumption is stated.
- **Advise on this job only.** Not the business, not taxes, not strategy.
- **Missing data over a wrong guess.** If the data can't support a finding, name the gap instead of filling it.
