# The Job-Costing Diagnostician

Reads a finished trades job that was **bid to be profitable but came in under its target margin**, and names the single reason the money leaked out between the quote and the final invoice. It shows the number trail that proves it, then stops.

Built for **bookkeepers and accountants** closing out jobs for service-trade clients — roofing, plumbing, HVAC, electrical, remodeling. Contractors can run it directly too; the evidence is the same either way.

---

## How to use it

Drop this folder into a Claude Project (or a Gemini Gem, or a custom GPT), point it at a finished job, and ask why it lost money.

Or attach the folder and say **"hi"** — it introduces itself and walks you through in plain English. Nothing to read first.

**Deploying it in a practice:** keep **one** copy at the root of your ICM, with client and job folders beside it — never a copy inside each job folder. Five files duplicated across forty jobs is forty copies drifting apart, the exact failure folders-as-architecture exists to prevent. How the job folders get filled is up to you (dragged in by hand, or synced from a shared drive on a schedule); none of that is required. It reads whatever is in a job folder the moment you point at it.

### Try it in two minutes

Finished job folders ship next to this one — real-shaped messes of photos: receipts, day logs, text threads, an inspection tag, a sticky note asking where the money went.

**Test it with `Reyes panel upgrade 44 Thistle Rd`.** It is deliberately **not** worked anywhere in `examples.md`, so nothing in this folder contains its answer. (`Mrs. Hendricks` and `Whitfield` *are* worked, as calibration — feeding those back is a memory test, not a diagnosis.)

Reyes is also the sharper test. It looks like a plain labor overrun — 46 hours against 30 quoted, and the contractor's own note says exactly that. The hours are a symptom, and the evidence for the real cause is a photograph of an inspection tag.

## What to feed it

**A shoebox is fine — that's the point.** It reads a real job folder, not a clean spreadsheet. It pulls the numbers out itself and names what's missing rather than guessing.

- The **estimate** — bid price and the cost breakdown behind it (materials, labor hours, labor rate, equipment, subs).
- The **actuals** — receipts, real hours, and what was actually **collected**, not just invoiced.
- The **paperwork around the edges** — texts, crew notes, inspection notices, voicemails. Not decoration: once the numbers locate the bleed, these are usually what identify the cause.

## What it does

1. Inventories the folder, splitting **numeric** artifacts (which bucket bled) from **narrative** ones (why).
2. Establishes target margin, actual margin, and the gap between them — the **bleed**.
3. Breaks the bleed into buckets and **reconciles**, so no lost dollar goes unexplained.
4. Ranks the buckets and finds the single cause behind them.
5. Separates **cause from symptom**.
6. States **one** diagnosis, shows its reasoning, names what it ruled out, and stops.

## What it will NOT do (by design)

- It won't rewrite the estimate. (That's an editor.)
- It won't hand you a checklist of everything a little off. (That's an audit.)
- It won't jump to "here's what to do instead." (That's a consultant.)

It answers exactly one question: **why did this job bleed?**

---

## Folder structure

Five things, each doing one job:

| File | Its one job | Answers |
|---|---|---|
| `README.md` | How to use it, what to feed it | *Where do I start?* |
| `identity.md` | Who it is, what it refuses to be, how it writes | *Who's talking?* |
| `rules.md` | The method, Step 0 → 7 | *What do I do next?* |
| `examples.md` | Calibration — the standard of proof | *How good must this be?* |
| `reference/failure-modes.md` | The catalog: what a measurement means | *Which failure is this?* |
| `reference/frameworks.md` | The math: how to take a measurement | *What is this number?* |
| `reference/benchmarks.md` | Trade ranges for sanity checks | *Is this number unusual?* |

**Nothing is duplicated between them**, and the boundaries sit where they would otherwise blur:

- `frameworks.md` computes proportionality; `failure-modes.md` says what a proportional overrun *means*. Measurement, then interpretation — never both in one file.
- `rules.md` Step 7 checks the **output** (did I stop, or drift into advice?); `frameworks.md` §7 checks the **reasoning** (does my cause actually hold?).
- `identity.md` states what it refuses to be as *character*; `rules.md` states the same as *constraints on the draft*.

`rules.md` is method and stays stable across every job. `reference/` is knowledge and grows as you meet new failure modes. `examples.md` is calibration. Each extends without touching the others — the whole argument for a folder over one long prompt.
