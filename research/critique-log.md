# Critique Log

Objections received, the reply, and what changed. An entry that currently wins stays marked `OPEN — UNANSWERED`; the log exists to record the state of the argument, not to flatter the thesis.

This log is seeded with the strongest objections known to us at launch — including ones we cannot yet answer. A critique log that begins empty is a claim; one that begins with unanswered entries is a working mechanism.

**Entry format:** ID · date · source · target · objection · current reply · what changed · status.

---

## C-001 — The thesis risks unfalsifiability in practice

**Date:** 2026 · **Source:** self-critique, pre-launch · **Target:** the hypothesis

**Objection:** "Adaptive capacity" and "learning preservation" are flexible enough that any outcome could be reinterpreted as consistent with the thesis. A hypothesis that survives every outcome is not a hypothesis.

**Reply:** Accepted as the central risk. The mitigation is procedural, not rhetorical: predictions are registered with frozen wording and pre-committed measures (see `predictions.md`), and P-003 is explicitly flagged as *not yet resolvable* until its proxies are fixed. The thesis is only as falsifiable as its ledger discipline.

**What changed:** Operationalization-notes field added to every prediction; rule added that scoring methods must be committed before data collection.

**Status:** `OPEN — STANDING RISK` (this objection can never be fully closed; it is a constraint to be continuously satisfied)

---

## C-002 — Calibration training may not transfer

**Date:** 2026 · **Source:** self-critique, from the judgment & decision-making literature · **Target:** P-001 / Brain Gym premise

**Objection:** Decades of debiasing research show that training effects are often domain-specific and decay over time. People can improve calibration on practice items while remaining poorly calibrated on real decisions. If loop-closing practice improves performance only inside the training environment, Brain Gym is a game, not infrastructure.

**Reply:** Not currently answerable with our data, because we have none. This is precisely what P-001's design must confront: the measure deliberately uses *real logged decisions*, not synthetic practice items, to make transfer the thing being tested rather than assumed.

**What changed:** P-001's operationalization specifies real decisions; the Brain Gym roadmap line "released when it can generate evidence, not before" exists because of this objection.

**Status:** `OPEN — UNANSWERED`

---

## C-003 — Frontier models may absorb the layer

**Date:** 2026 · **Source:** self-critique · **Target:** the hypothesis (claim 5) / the framework

**Objection:** If frontier AI systems internalize calibration support, assumption tracking, and learning preservation natively, external scaffolding adds no marginal value and the entire infrastructure layer is a temporary patch on a closing gap.

**Reply:** Listed as failure mode #1 on the public site, deliberately. The current bet is that *human* calibration is not improved by an AI being well-calibrated on the human's behalf — you cannot outsource your iterations. But that is the bet, not a fact, and it is exactly what P-001 versus increasingly capable baseline assistants would test.

**What changed:** The "you cannot outsource your iterations" claim was sharpened from a slogan into the load-bearing assumption that distinguishes this objection's world from ours.

**Status:** `OPEN — UNANSWERED`

---

## C-004 — The evidence cases are post-hoc pattern matching

**Date:** 2026 · **Source:** self-critique · **Target:** the formalisation / evidence

**Objection:** Lidl/SAP, Boeing 737 MAX, Enron, and the Abilene Paradox are offered as instances of the Apparency Error, but complex failures admit many framings, and selecting famous disasters that fit the frame is survivorship of the narrative. The formalisation Aₐ − Aₘ = ΔE is not currently a measurement; it is a description wearing the clothes of one.

**Reply:** Partially conceded. The cases demonstrate that the *pattern exists and is expensive*, which is the claim made on the site — they do not and cannot demonstrate that ΔE is measurable or that reducing it upstream is tractable. The formalisation's status is "named and defined," not "quantified." Quantification is open work, and the notation should not be allowed to imply more precision than exists.

**What changed:** Evidence cases are documented in `evidence/` with the limited claim they support stated explicitly at the top of the file.

**Status:** `OPEN — PARTIALLY CONCEDED`

---

## Submitting a critique

Via the [contact page](https://sachakuxanda-arch.github.io/third-intelligence/contact.html?type=critique) (select what your critique targets) or by opening an issue. Entries are logged with attribution unless you ask otherwise.
