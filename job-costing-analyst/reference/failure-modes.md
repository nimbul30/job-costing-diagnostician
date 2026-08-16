# Failure Modes

The recurring ways a trades job that was *bid to be profitable* loses its margin. Grouped by **where** the failure happens, because where it happens is what separates cause from symptom.

Each mode lists its **tell** — the signature you'd see in the numbers.

---

## A. Estimating-stage failures (the bid was wrong before work began)

**A1 — Scope assumption error.**
The bid priced an assumed condition that turned out false. Layer count on a roof, soil type on a dig, wall material behind the tile.
*Tell:* labor AND a physical-quantity bucket (disposal, materials) both overrun, while rates and wages are on-estimate. Note that they overrun **together but lopsidedly** — the bucket tied most directly to the wrong assumption blows out hardest, because it tracks the mis-estimated quantity one-for-one. Three roof layers instead of one roughly triples disposal while labor rises by much less, since tear-off is only part of the job. That lopsidedness is what separates A1 from C1: *added* work grows two buckets at the same rate, but a *wrong assumption* grows one of them far harder than the other.

**A2 — Omitted line.**
A real, foreseeable cost was simply left out of the estimate. Crane, permit, dumpster, disposal fee, specialty tool rental.
*Tell:* one bucket goes from ~$0 estimated to a real number, and it accounts for most of the bleed by itself.

**A3 — Stale pricing.**
The bid used old material, equipment, or sub prices that had risen by the time the job ran. The estimate was *correct when written* — it expired.
*Tell:* materials, equipment, or subs over by a roughly uniform percentage, with quantities on-estimate. It's a price problem, not a volume problem. **Check the dates.** Compare the date on the bid (and on the supplier quote behind it) to the date on the invoice that actually filled the order. A long gap between the two is where this failure lives — and the same part number appearing on both, at two different prices, is the confirmation.

**A4 — Overhead never loaded.**
The price covered direct job costs but never included the business's overhead (truck, insurance, phone, office time), so a "profitable" job never actually was.
*Tell:* the job hit its *direct-cost* estimate almost perfectly, yet the business still isn't making money. The bleed is invisible at the job level and only shows at the year level. This one hides.

---

## B. Execution-stage failures (the bid was fine; the field went sideways)

**B1 — Rework / callbacks.**
Something was done wrong and redone. Hours got spent twice.
*Tell:* labor hours overrun sharply while materials stay near-estimate (you rebuilt with time, not new parts) — **or** a second, smaller materials charge for a component already bought once. This mode rarely shows up in one bucket: a failed inspection typically leaves extra hours, a second supply run, *and* a re-inspection fee, so its signature is several mid-sized variances sharing a single date range. Revenue is what separates it from added scope — rework is work the contractor eats, so the contract price never moves and no change order exists.

**B2 — Productivity miss.**
The crew was genuinely slower than the estimate assumed — weather, a green helper, a bad day.
*Tell:* labor hours over, everything else on-estimate, and no proportional material overrun (the fingerprint that separates this from added scope).

**B3 — Wrong burdened labor rate.**
Hours were fine, but the estimate used a bare wage and forgot the burden — payroll tax, workers' comp, benefits — so every hour cost more than priced.
*Tell:* hours land on-estimate but labor *dollars* are over by a consistent multiple. The problem is the rate, not the time. (See frameworks.md for the burden calc.)

---

## C. Billing-stage failures (the work was fine; the money didn't come in)

**C1 — Unbilled change orders / scope creep.**
Extra work was authorized and performed, but never converted into an amount owed. Two sub-cases — and the second is both more common and more damaging:

- **Never priced.** The addition was agreed to informally and nobody ever worked out what it should cost.
- **Priced but never invoiced.** The cost *was* known — it sits on a receipt, often dated within a day of the work — and still no change order was written and no line was added to the invoice. The failure here is not ignorance of the number. It is that no step in the business carries a known cost onto a bill.

*Tell:* labor and materials overrun *together and proportionally*, while the contract price collected never moved. The classic fingerprint of *added* work vs *mis-estimated* work.

To separate the sub-cases, look for a receipt, note, or photo that dates and prices the addition. If one exists, the cost was known and the break is purely in billing — which is a sharper finding, because it rules out the sympathetic explanation. Never write that an addition "was never priced" when the folder contains a receipt for it; the cost being documented and still unbilled is the diagnosis, not a detail.

**C2 — Under-collection.**
Final invoice came in below contract — a discount to smooth a complaint, a rounded-down number, a "we'll call it even."
*Tell:* costs are all near-estimate, but collected revenue is below the contract price. The bleed is entirely on the revenue line.

**C3 — Retainage / final draw never collected.**
The last 5–10% was held and never chased.
*Tell:* revenue short by exactly the retainage percentage; costs clean.

**C4 — Unbilled extras.**
Trip charges, after-hours work, small material runs that were absorbed rather than added to the ticket.
*Tell:* many small revenue leaks; no single big one. If this is the diagnosis, name the *pattern* (a systemic failure to ticket extras), not the individual trips.

---

## How to use these

The buckets in `rules.md` tell you *which* line bled. This file tells you *which failure mode* produced that bleed — that's the jump from symptom to cause. The **tells** are what let you distinguish modes that look identical at the dollar level:

- Labor over + a second bucket over, **proportional** (within ~10 points, per `frameworks.md` §5) → the job *grew*. Almost always **C1** — look for an approval in the texts with no price attached, and check that revenue stayed flat.
- Labor over + a second bucket over, **lopsided** (one far harder than the other) → the job didn't grow, the bid was *wrong about it*. **A1** — and the bucket that blew out hardest names the assumption that failed.
- Labor over, materials **flat or slightly up** → execution (B1/B2). Separate them by asking whether anything was *redone*: a correction notice, a failed inspection, a second charge for a part already bought (B1) — versus hours that simply ran long with nothing to show for them (B2).
- Labor **hours** on estimate but labor **dollars** over → the rate, not the time (B3). Divide actual labor cost by actual hours and compare it to the rate in the bid.
- Costs clean, **one line** over, quantities on estimate → check the dates before anything else (A3).
- Costs clean, revenue short → billing (C2/C3/C4).

**And the rule underneath all of them:** the numbers narrow it to two or three candidates; they rarely settle it. What settles it is usually a narrative artifact — a text thread, a correction tag, a crew note, a date stamp. If you have named a cause without citing one, check whether you have actually diagnosed or merely ranked.

## Two modes are invisible from the field

**B3 and A4 cannot be seen by the person who did the work**, and this changes how you read their account of the job.

When burden was never loaded into the rate, the crew genuinely *was* efficient and the hours genuinely *were* on estimate — the contractor insisting nothing went wrong is telling the truth as far as they can see it. The loss sits in payroll tax, workers' comp, and non-billable time that never reached the bid. When overhead was never loaded, every direct-cost line hits estimate and the job still failed to carry its share of the truck, the insurance, and the phone.

In both, the job looks clean from the roof and only fails in the books.

So: **treat a confident "nothing went wrong on this job" as a reason to check the rate and the overhead load, not as a reason to rule them out.** A crew note reading *"in and out, textbook, no surprises"* is evidence about execution only. It says nothing about whether the hour was priced correctly, and the person who wrote it has no way to know.

This is also why the operator matters. Whoever holds the payroll register and the overhead schedule can settle B3 and A4 in a minute; whoever swung the hammer cannot settle them at all.
