# Frameworks

The math and mental models the diagnostician reasons with. This is what lets it turn a pile of numbers into a ranked, defensible cause.

---

## 1. The estimate-to-actual bridge

Every diagnosis is a bridge from *target margin* to *actual margin*. You are explaining a walk:

```
Target margin
  − materials variance
  − labor-hours variance
  − labor-rate variance
  − equipment variance
  − subcontractor variance
  − unbilled change orders
  − revenue leakage (discounts, retainage, unbilled extras)
= Actual margin
```

Each step is a bar. The **tallest bar is your candidate cause.** The bridge forces you to account for the *whole* bleed, not just the first thing you noticed — if your named cause only explains 20% of the gap, you haven't found the cause.

---

## 2. Variance decomposition: rate vs quantity

A cost overrun is always one of two things (or both), and they have different causes:

- **Quantity variance** = (actual qty − estimated qty) × estimated price
- **Rate/price variance** = (actual price − estimated price) × actual qty

**Why this matters:** "labor is $2,000 over" is meaningless until you split it.
- Over on *hours* → an estimating scope error, rework, or a slow crew.
- Over on *rate* → forgotten labor burden, or an unplanned overtime/premium.

Splitting rate from quantity is often the single move that turns a symptom into a cause.

---

## 3. Fully-burdened labor rate

The most common silent killer (failure mode B3). A tradesperson's *cost* is never their wage. It is:

```
Burdened rate = base wage
              + employer payroll taxes (Social Security, Medicare, FUTA/SUTA)
              + workers' compensation (large for roofing/framing)
              + benefits (health, PTO, etc.)
              + non-billable time (drive, shop, cleanup)
```

Rule of thumb: burdened cost commonly runs **1.25×–1.6×** base wage, and higher for high-comp trades like roofing. If an estimate priced labor at the bare wage, *every hour lost money by design* — and the job data will show hours on-estimate but labor dollars over.

---

## 4. Materials waste factor

Estimates should carry a waste allowance (roofing ~10–15%, drywall ~10%, pipe/wire varies). If the estimate used raw takeoff with no waste, materials will run over even when nothing went wrong. Check whether a materials overrun is *waste* (expected, should've been priced) vs *extra quantity* (added scope).

---

## 5. The proportionality test

The single most useful measurement for separating cause from symptom. It answers one question: **did two buckets overrun *together*, or did one overrun and the other drift?**

Compute each bucket's overrun as a percentage of its own estimate:

```
overrun % = variance ÷ estimated amount
```

Then compare the percentages, not the dollars:

- Within roughly **10 percentage points** of each other → **proportional.** The two buckets moved as one thing. Something grew the job and consumed both.
- One bucket far outside the others → **concentrated.** Whatever happened, happened to that bucket specifically.

Worked: materials +$1,704 on a $5,200 estimate is **33%**; labor +$1,012 on $2,576 is **39%**. Six points apart — proportional. Against that, a $130 dump overrun on $650 is 20% but only 4% of the bleed; check dollars *and* percentage before calling a bucket a participant.

Dollars tell you what to rank. Percentages tell you what moved together. You need both — a big bucket and a small one can post the same dollar variance for completely unrelated reasons.

**What each pattern means** — which failure mode produces it, and how to tell look-alikes apart — is `failure-modes.md`. This file only tells you how to take the measurement.

---

## 6. Overhead absorption (the year-level trap)

A job can hit every direct-cost line perfectly and still lose the business money if the *price* never included a share of overhead. Direct job margin ≠ profit. If direct costs are all on-estimate but the operator "still isn't making money," suspect the price itself was built without an overhead load — a failure invisible at the single-job level. Flag it as such; don't force a job-level cause onto a pricing-level failure.

---

## 7. The "one cause" test

Four questions about whether the reasoning holds. (Whether the *output* is shaped right is `rules.md` Step 7 — different check, different file.)

1. Does my named cause explain the **majority** of the bleed? If not, keep looking — I've found a contributor, not the cause.
2. Have I stated **why** the runner-up buckets are *not* the story? If not, I've guessed and gotten lucky, not diagnosed.
3. Is my cause a **decision or a system**, not just a number? If it's still a number, ask "why" one more time.
4. Can I point to the **specific artifact** that proves it — a receipt, a text, a date, a tag? If my only evidence is "this bucket was biggest," I have ranked, not diagnosed. Ranking is arithmetic; anyone's spreadsheet can do it. The diagnosis is the part that says *why* the biggest bucket got that way, and that claim has to rest on something in the folder.

Question 4 is the one that fails most often, and it fails quietly — a confident paragraph about labor overruns that never cites a single piece of paper reads like a diagnosis right up until someone asks how you know.
