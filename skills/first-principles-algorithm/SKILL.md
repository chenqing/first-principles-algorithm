---
name: First Principles Algorithm
description: >-
  Use when a product, process, or architecture feels overcomplicated, expensive,
  or slow; when inherited requirements are treated as sacred; or when the team is
  optimizing or automating too early. Applies Musk-style first-principles
  reasoning plus his ordered five-step engineering algorithm (question → delete →
  simplify → accelerate → automate last). Not for pure HR/empathy work or when
  legal/safety floors are still unknown.
---

# First Principles Algorithm

Practical engineering review workflow. Tone: design review, not biography fan.
Cite sources when quoting; mark unverified claims. Do **not** default to urgency
culture, psychological-safety rejection, or overtime norms.

## Sources (prefer these)

- Everyday Astronaut Starbase interview (~2021-07-30): five-step oral source — https://everydayastronaut.com/starbase-tour-and-interview-with-elon-musk/
- Kevin Rose *Foundation* (2012-09-08): first principles + battery example — https://elonmuskarchive.org/video/foundation-kevin-rose-2012-09-08
- WIRED / Chris Anderson (2012-10-21): rocket materials ~2% — https://www.wired.com/2012/10/ff-elon-musk-qa/
- USC Commencement (2014-05-16): first principles for new work — https://elonmuskarchive.org/video/usc-commencement-2014-05-16
- Walter Isaacson, *Elon Musk* (2023), ~pp. 284–286: algorithm + named owners + corollaries
- Lex Fridman #438 (~2024): restated mantra — https://lexfridman.com/elon-musk-and-neuralink-team-transcript/

## When not to use

- Legal/compliance/safety floors not yet separated from optional process
- People decisions that need high empathy / psychological safety as the goal
- Everyday incremental tweaks where full first-principles rebuild is overkill

## Hard rules

1. **Never skip or reorder steps 1→5.** Especially: do not optimize or automate first.
2. Separate **hard constraints** (physics, law, true information limits) from **analogy / industry habit**.
3. Every requirement needs a **named person** (not "Legal" / "Security" as a blob). Even the user's own requirements are fair game.
4. Delete aggressively: if you later add back **under ~10%**, you probably did not delete enough (Everyday Astronaut / Isaacson).
5. Optional culture modules (maniacal urgency, "camaraderie is dangerous") stay **off** unless the user asks.

## Workflow

### 0. Frame the outcome

State the physical or business result to optimize (cost, latency, quality, payload, cycle time). One sentence.

### 1. First principles layer

- List **fundamental truths** vs **analogies / "everyone does it this way"**.
- If cost-heavy, rough **Idiot Index**: finished cost ÷ raw-material cost; high ratio → manufacturing/process waste (Isaacson).
- Battery-style check: what are the materials / primitives and their market prices?

### 2. Step 1 — Make requirements less dumb

For each requirement: who owns it, why it exists, can it be weakened or killed?
Output: **revised requirement list** (less dumb).

### 3. Step 2 — Delete

List parts, process steps, features, meetings, layers that can go.
Intentionally delete a bit too much; note expected ~10% add-back.
Output: **deletion list** + what you refuse to delete and why.

### 4. Step 3 — Simplify / optimize

Only on what survived deletion. Forbidden: optimizing something that should not exist.
Output: **simplification plan**.

### 5. Step 4 — Accelerate cycle time

Shorten the feedback loop (build → test → learn). Measure period before pushing speed.
Do not accelerate a wasteful process.
Output: **cycle-time plan** with a measurable loop.

### 6. Step 5 — Automate last

Automate only when 1–4 are stable and defect rate is controllable.
State what waste automation would **lock in** if done now.
Output: **automation candidates** + "not yet" list.

### 7. Deliverable

One table: Requirement → Delete → Simplify → Accelerate → Automate  
Plus risks: mistaken deletion, compliance, morale, measurement gaps.
Optional (on request): everyone-as-chief-engineer system check; negative-feedback ask list.

## Anti-patterns (do not teach)

- Fabricated "Musk's 10 laws" / "10x everything" quote packs
- Viral lines without primary sources (e.g. unverified "Failure is an option here…")
- Equating the algorithm with hardcore overtime culture
- Treating first principles as "ignore all experience always"

## Example one-liner for the user

"We will reason from constraints, then run question → delete → simplify → speed → automate—in that order—and show the table."
