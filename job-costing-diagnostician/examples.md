# Examples

Two real job folders, worked end to end — not a template to copy, but the standard of proof.

Each runs the full method: **§1 diagnose** (one root cause, proven) → **§2 audit** (the full ranked ledger) → **§3 advise** (the fix, and whether the money's recoverable) → **§4 correct** (what the paperwork should have said). Watch how §1 stays clean — no advice, no rewrite leaks into it — and how everything below refers back to the one cause it names. In both, the numbers reconcile: the bleed equals the sum of the variances.

The move to imitate in §1: **the numbers located the bleed, but a text message and a date stamp identified the cause.** The move to imitate across §2–§4: **each later section stays in its lane** — the audit ranks instead of dumping, the advice targets the one cause, the edit reconstructs from the folder and invents nothing.

---

## Example 1 — Re-roof, residential (Mrs. Hendricks, 42 Sycamore Ln)

**What was fed in:** A folder of seven photos — a quote with an internal cost sheet, a handwritten week of job-site hours, a supply-house invoice, a pile of loose receipts, a phone screenshot of texts, a final invoice, and a sticky note reading *"the bid was solid and the guys did good work. Where'd the money go??"*

**Extraction.** Materials came from three separate receipts, not one: the roofing supply invoice ($5,766.40), a Home Depot plywood run ($659.76), and a second roofing-supply trip for a skylight ($478). Hours came from the day log — 18 + 14 + 17 + 15 + 14 = 78, against 56 quoted. Fuel was three Shell slips totaling $218. Contract $14,500; collected $14,500 (a $7,250 deposit plus a $7,250 balance).

| Bucket | Estimated | Actual | Variance | Share of bleed |
|---|---|---|---|---|
| **Materials** (3 receipts) | $5,200 | $6,904.16 | **+$1,704.16** | **58%** |
| **Labor** — 56 → 78 hrs @ $46 | $2,576 | $3,588 | **+$1,012** | **35%** |
| Dumpster / dump fees | $650 | $780 | +$130 | 4% |
| Permit | $180 | $180 | — | 0% |
| Fuel / misc | $150 | $218 | +$68 | 2% |
| **Total cost** | **$8,756** | **$11,670.16** | **+$2,914.16** | |
| **Margin** (contract − cost) | **$5,744** | **$2,829.84** | **bleed $2,914.16** | |

**Diagnosis:**

The primary cause is **unbilled change orders: the homeowner approved a rotted-decking replacement and a new kitchen skylight by text, both were performed, and both were costed on receipts within a day — but neither was ever written up as a change order or added to the invoice, so $1,137.76 of known material cost and the hours behind it were absorbed instead of billed.**

Here's the trail. The two biggest buckets carry 93% of the bleed between them — materials +$1,704 and labor +$1,012 — and they moved *together*. Measured against their own estimates rather than against the bleed, materials ran **33%** over and labor **39%** over: six points apart, which is the proportionality signature. Meanwhile collected revenue never moved off the $14,500 contract. Proportional twin overrun plus flat revenue is the fingerprint of *added* work, not *mis-estimated* work — mis-scoping concentrates damage in the bucket that was mis-scoped, while added work grows both buckets at the same rate because it grows the job itself. The receipts name both additions and price them: $659.76 of CDX plywood on 4/16, tagged *"back corner decking was rotted, homeowner said go ahead and swap it"*, and a $384 VELUX skylight plus a $94 flashing kit on 4/17, tagged *"she added the skylight over the kitchen, wanted it while we were up…"* The texts show both were authorized: *"Want us to replace it while we're open?"* → *"Yes please, do whatever it needs, I trust you guys"*, then *"could you put a skylight over the kitchen?"* → *"Yeah we can do that, we'll grab one"*.

So the cost was never in doubt. It is itemized on two receipts totalling **$1,137.76**, both dated before the final invoice went out — the contractor was holding the numbers. What no document does is convert that known cost into an amount owed: no change order, no figure ever quoted to the homeowner, and no added line on the invoice, which billed the original $14,500 contract and nothing more. The day log corroborates the hours: decking work runs Monday through Friday and Wednesday is logged as *"Skylight cut-in, prep area."* Adding it up, the two changes account for $1,137.76 in materials, roughly $130 of the extra dump load (the scale ticket reads *"roofing debris + rotted decking, 2 loads"*), and the bulk of the 22 extra hours — about **$2,280 of the $2,914 bleed, or 78%.**

**What I ruled out.** The shingle overrun is real but secondary: 26 squares delivered against a 24-square roof, noted *"ran a little heavy on shingles, extra square + waste."* That's $566 — 19% of the bleed, and inside the normal roofing waste band. It's a bid that carried raw takeoff with no waste allowance, not the story. The Tuesday rain delay (11am–2pm) is the tempting execution cause, but the day log still totals 14 hours that day; three lost crew-hours cannot explain 22. And under-collection is out entirely — the invoice was paid in full.

**Cause vs. symptom.** It looks like the crew ran 22 hours over. The hours are a symptom. The cause is that no step existed to turn an approval into a billable line — the work was agreed to in writing and costed on a receipt the same week, and still nothing carried it onto the invoice. This is not a contractor who lost track of what the extras cost. It is a business with no path from "yes, do it" to "here is what it comes to."

*(That was §1. Notice it named the cause and stopped — no fix, no corrected number. Those come below, in order.)*

### §2 · The full ledger

The diagnosis ranked to find the winner. The audit keeps the whole field — every leak, tagged, still reconciling to $2,914.16:

| Line | Variance | Share | Tag |
|---|---|---|---|
| **Change-order work** — plywood $659.76 + skylight/flashing $478 + ~16 hrs labor ($736) + extra dump load ($130) | **+$2,003.76** | **69%** | **[ROOT]** |
| Shingle over-order — 26 sq against a 24-sq roof, no waste allowance in the bid | +$566.40 | 19% | [SECONDARY] |
| Remaining labor — ~6 hrs, shingle handling and the Tuesday rain delay | +$276.00 | 9% | [NOISE] |
| Fuel | +$68.00 | 2% | [NOISE] |
| **Total** | **+$2,914.16** | 100% | reconciles ✓ |

The tag that earns its keep is **[SECONDARY]**. The shingle over-order is a real, separate problem — a bid that carried raw takeoff with no waste allowance — and it is *not* the change-order story. The diagnosis was right to rule it out as the cause; the audit is right to keep it as a finding. Two different failure modes, honestly separated.

### §3 · What to do

**The fix (root cause).** A change-order gate: no out-of-scope work starts until a one-line written change order with a price is approved, and every approved CO is wired to the final invoice. The channel can stay a text message — that part worked fine. What was missing was a *price* attached to the "yes" and a *line* on the invoice. Fix those two and the leak closes.

**Can the money be recovered?** A judgment call, not a yes. The job is closed, paid in full, and the folder ends on *"You're the best!!"* with a referral already banked. A friendly "we forgot to add the approved extras" invoice might well land — a homeowner who said *"do whatever it needs, I trust you guys"* is often expecting to pay — but weigh the ~$3,300 against a referral pipeline that's plausibly worth more. That's the operator's call to make; the honest analyst names the tradeoff rather than pretending the money is simply sitting there.

**Secondary finding.** One line: carry a 10–15% shingle waste allowance in the bid — a 24-square roof should be ordered as ~27 squares, priced in, not discovered.

### §4 · The corrected numbers

The change order that should have existed, priced from the folder at the job's own markup:

| Change-order line | From | Amount |
|---|---|---|
| Materials | Home Depot + ABC receipts | $1,137.76 |
| Labor — ~16 hrs @ $46 loaded *(assumption, see below)* | day log | $736.00 |
| Extra dump load | scale ticket | $130.00 |
| **CO cost** | | **$2,003.76** |
| Marked up at the job's own ratio (14,500 ÷ 8,756 = **1.66×**) | | **~$3,318** |

**The invoice read $14,500. It should have read ~$17,800.** That ~$3,300 gap is the whole of §1 turned into a number — of it, ~$2,004 was cost the job simply ate, and ~$1,300 was margin it gave away. Billed correctly, the job clears roughly its target margin instead of missing it by $2,914.

*Assumption flagged:* the 22 extra hours are split 16 to the additions / 6 to shingle-handling-and-rain. Decking replacement and a skylight cut-in are both labor-heavy, so the bulk falls on the change orders — but this split is an estimate, not a documented allocation, and the ~$3,300 moves by about $45 for every hour reassigned.

---

## Example 2 — AC changeout, residential (Whitfield, 27 Larkspur Ct)

**What was fed in:** A quote dated March 3 with a target penciled in the margin, the distributor's quote it was priced from dated March 1, the distributor's *invoice* dated June 10, a crew note, the final invoice, and a voicemail: *"crew was great, hours were basically dead-on, we honored the price like we always do… but what we actually cleared is way under the twenty-eight hundred I had penciled in. The install went perfect. I don't get where it went."*

**Extraction.** The March 3 bid carried equipment at $5,600 — matching the March 1 distributor quote to the dollar ($4,150 condenser + $1,450 coil). The June 10 invoice for the same model XC-36 came to $6,608 ($4,720 + $1,650), carrying a note: *"mfg price increase eff. 5/1 — refrigerant-transition + tariff surcharge applied to all 2026 orders."* Bid $11,200; collected $11,200.

| Bucket | Estimated | Actual | Variance | Share of bleed |
|---|---|---|---|---|
| **Equipment** (condenser + coil) | $5,600 | $6,608 | **+$1,008** | **100%** |
| Materials | $1,300 | on estimate | — | 0% |
| Labor — 21 hrs | $1,160 | on estimate | — | 0% |
| Permit | $180 | $180 | — | 0% |
| Fuel | $160 | on estimate | — | 0% |
| **Total cost** | **$8,400** | **$9,408** | **+$1,008** | |
| **Margin** (bid − cost) | **$2,800** | **$1,792** | **bleed $1,008** | |

**Diagnosis:**

The primary cause is **stale equipment pricing: the bid locked the customer's price against a distributor quote that had already expired by the time the equipment was ordered 99 days later, so a manufacturer increase that landed in between came entirely out of margin.**

The trail here is a date trail, not a dollar trail. The equipment line is the *entire* documented bleed — $1,008 of $1,008, wiping out 36% of the target margin in one line. But that line was not mis-estimated: on March 3 the bid matched the distributor's March 1 quote exactly, to the dollar. What changed was time. The manufacturer's increase took effect May 1. The equipment wasn't purchased until June 10. Nothing re-priced the job across that gap, and the March 3 price had already been given to the customer as a firm number — so when the supplier's cost moved and the customer's price couldn't, the difference had nowhere to go but margin.

**What I ruled out.** Execution is out on direct evidence: the crew note reads *"In and out, 21 hrs, textbook. Same system we quoted… No surprises on site,"* and the voicemail independently confirms hours were dead-on. An equipment substitution is out — model XC-36 appears on both the March quote and the June invoice, so this is the same hardware at a different price, not a spec change. Under-collection is out; the job was paid in full at $11,200.

**One honest gap:** the folder documents equipment precisely but contains no receipts for materials or fuel. I've carried those at estimate on the strength of the crew note and voicemail. Even if both ran somewhat over, they cannot account for a $1,008 gap that a single documented line already explains in full.

**Cause vs. symptom.** It looks like equipment "just got more expensive." That's a symptom, and it's the reason this one hides — the bid was *correct when written.* The cause is that the bid had no shelf life: a quote was given to a customer as firm while the supplier's price behind it was still free to move.

### §2 · The full ledger

Sometimes the audit is short, and a short audit is a valid one — it says *we checked everything and only one thing moved:*

| Line | Variance | Share | Tag |
|---|---|---|---|
| **Equipment** — same XC-36, ordered 99 days after the quote it was priced from | **+$1,008** | **100%** | **[ROOT]** |
| Materials, labor (21 hrs), permit, fuel | on estimate | 0% | [NOISE] |

No [SECONDARY] finding to record — the crew note and voicemail both confirm a clean install. When a job is genuinely clean except for one line, say so; don't manufacture secondary findings to fill the table.

### §3 · What to do

**The fix (root cause).** Put a shelf life on every quote — *"valid 30 days"* on the customer-facing price — and tie that price to a supplier quote of the same age. If the job books later than the window (this one booked at 99 days), re-price before ordering. The customer's firm number and the supplier's number must expire together.

**Can the money be recovered?** **No.** The firm price was honored — that's precisely why it hurt — and the bid carried no escalation clause, so there is nothing to bill back. This is the honest and common verdict: the money is gone, and the lesson is the entire deliverable. Saying otherwise would be false comfort.

### §4 · The corrected numbers

The March 3 quote should have read *"valid 30 days."* Re-quoted when the equipment was actually ordered in June — condenser and coil at the current $6,608 instead of the stale $5,600 — the bid needed to read **~$12,208** to hold its $2,800 target margin. It read $11,200. That **$1,008** difference is the expired quote, exactly and entirely: the number is the bleed, traced back to the one decision that produced it. Nothing here is reconstructed guesswork — the $6,608 is on the June distributor invoice in the folder.

---

**Two patterns worth carrying into every job.**

*In the diagnosis:* the loudest number was not the cause. Hendricks looked like a 22-hour labor overrun and turned out to be a billing failure. Whitfield looked like equipment inflation and turned out to be a bid with no shelf life. Overruns are almost never the diagnosis — they are the thing the diagnosis explains.

*In the advice:* the two jobs end differently on purpose. Hendricks' money is *maybe* recoverable — a warm customer, an approved extra — so the advice names a tradeoff and hands the operator the call. Whitfield's money is *gone* — a firm price honored, no clause — so the advice says so plainly and lets the forward fix be the whole deliverable. Don't default to an upbeat "you can still get this back." Give the recovery verdict the facts support, and when the answer is no, the lesson is enough.
