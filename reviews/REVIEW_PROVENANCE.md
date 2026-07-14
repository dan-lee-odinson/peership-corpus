# Review provenance — the per-paper record

**Each paper in this corpus ran its own review cycle before it was deposited.** They were not reviewed together. There is no single review of the corpus as a whole, and none is claimed.

This document exists because the corpus was, briefly, at risk of claiming one. The four-round adversarial chain that concluded on 14 July 2026 with a PASS belongs to **paper V, *The Peership Thesis*** — not to the corpus. Papers I, II and IV cleared their own, earlier, and in some cases harsher gates. Citing paper V's PASS as though the whole corpus had passed a four-round review would be exactly the kind of credential inflation the claim ledger exists to prevent.

## What these documents are, and are not

Review documents are **non-authoritative**. Where a review and a frozen paper or the synchronized apparatus conflict, the paper and the apparatus control.

These reviews were conducted by prompting large language models to attack the drafts. That is **quality control, not peer review**: no journal, no editor, no independent human referee. The papers are preprints and have not been peer reviewed. The author (Dan Lee-Odinson) is the sole human author and the responsible party for every disposition; nothing was accepted or rejected by a model.

**Nothing in this process is evidence of machine political agency, consciousness, or standing.** A model that produces a sharp objection has produced text. That the text was useful is a fact about the tool and the author's use of it, not a fact about the tool's standing. A corpus arguing about the conditions of machine political membership has to be scrupulous here, because the cheat would be obvious and fatal.

## The prompts are published

The two surviving adversarial-review prompts for *Peership* are committed here:

- [`02-peership/PROMPT_round1_adversarial_review.md`](02-peership/PROMPT_round1_adversarial_review.md)
- [`02-peership/PROMPT_round2_integration_audit.md`](02-peership/PROMPT_round2_integration_audit.md)

They are published deliberately, because the strongest objection to a self-administered adversarial review is that nobody can tell whether the reviewer was told to attack hard or to bless. A reader can now check. The round-1 prompt directs the draft to be pasted into "GPT-5 / a non-Anthropic model" — a model from a different lineage than the one that drafted the essay — and demands the killing objection, a citation hit-list, an AI-tell hit-list, and "the objection I could not answer."

Prompts are published; **chat transcripts are not**, and no private material is exposed.

## Per-paper record

### I. *Gods and Slaves* (v1.2 deposited)

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`01-gods-and-slaves/cross_essay_review_v1.1.md`](01-gods-and-slaves/cross_essay_review_v1.1.md) | v1.1 | Adversarial cross-essay review, judged against *Peership* v0.10 | **Revise before sequential publication** |

The review's charge was that the precursor contradicted its successor at the load-bearing joint — equivocating between subjecthood and peership, misclassifying theorists under its own taxonomy, distorting the *Dune* material, and misattributing citations. The verdict: *"Publish the essays in sequence only after revising the precursor to make its claims narrower and its terminology consistent with the successor."* The deposited version is **v1.2**, the revision that answered it.

### II. *Peership* (v1.0 deposited)

The longest chain in the corpus, and the harshest. The first review **failed** the draft outright.

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`02-peership/PROMPT_round1_adversarial_review.md`](02-peership/PROMPT_round1_adversarial_review.md) | v0.4 | **Review prompt** (to a non-Anthropic model) | — |
| [`02-peership/round1_adversarial_review_v0.4.md`](02-peership/round1_adversarial_review_v0.4.md) | v0.4 | Hostile expert adversarial review | **FAIL — major revision.** *"The central exclusivity claim does not hold."* Do not publish until resolved. |
| [`02-peership/round1_triage_v0.4.md`](02-peership/round1_triage_v0.4.md) | v0.4 | Author triage of the findings | Tiered into mandatory fixes, real hits, and reviewer overreach |
| [`02-peership/integration_audit_v0.5.md`](02-peership/integration_audit_v0.5.md) | v0.5 | Integration audit | — |
| [`02-peership/PROMPT_round2_integration_audit.md`](02-peership/PROMPT_round2_integration_audit.md) | v0.6 | **Review prompt** (round 2) | — |
| [`02-peership/integration_audit_v0.7.md`](02-peership/integration_audit_v0.7.md) | v0.7 | Integration audit | — |
| [`02-peership/integration_audit_v0.8.md`](02-peership/integration_audit_v0.8.md) | v0.8 | Integration audit | — |
| [`02-peership/integration_audit_v0.9.md`](02-peership/integration_audit_v0.9.md) | v0.9 | Integration audit | — |
| [`02-peership/confirmation_audit_v0.10.md`](02-peership/confirmation_audit_v0.10.md) | v0.10 | Confirmation audit | — |
| [`02-peership/round2_adversarial_review_v0.12.md`](02-peership/round2_adversarial_review_v0.12.md) | v0.12 | Round-two adversarial re-review (regression table) | **Split verdict** — the modest core claim survives; the stronger framing does not |
| [`02-peership/round2_triage.md`](02-peership/round2_triage.md) | v0.12 → v0.13 | Author triage and dispositions | v0.13 built and applied |
| [`02-peership/final_round_review_v0.13.md`](02-peership/final_round_review_v0.13.md) | v0.13 | Final-round publication-gate review | **Conditional pass** — make five publication-blocking corrections, then deposit |

The claim that did **not** survive round 1 is worth stating, because the corpus is better for having lost it: the original draft argued that Peership was the *uniquely* coherent stance, invariant under the power ratio. The reviewer rejected that exclusivity proof. What survived — and what the corpus now rests on — is the narrower distinction between welfare and constitutional standing. That is why the published corpus insists that welfare protection is a floor and not Peership.

### III. *The Isonomia Commons* (v1.1 deposited)

**Record pending.** A review cycle was run for this paper, but its record is not yet in this repository. It is not in the corpus's session outputs, and it is not in the [isonomia-path-a](https://github.com/dan-lee-odinson/isonomia-path-a) repository, which carries build-time `DECISIONS.md` and `BLOCKERS.md` rather than an essay-level review.

This slot is deliberately left open rather than filled with a guess or quietly dropped. It will be completed when the record is supplied. **No claim is made here about the scope, rigour, or outcome of that review until its document is in hand.**

Separately, and not a substitute for the above: the ISONOMIA *implementation* has its own evidence trail — a 45,000-run parameter sweep pinned to software release v1.0.0, commit `ba3ddb5` (DOI [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289)) — described in [`../implementations/isonomia.md`](../implementations/isonomia.md). Simulation evidence is not paper review, and those simulations establish sampled launch-economy behaviour only.

### IV. *Constitution, Not Cage* (v1.0 deposited)

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`04-constitution-not-cage/round1_adversarial_review_v0.1.md`](04-constitution-not-cage/round1_adversarial_review_v0.1.md) | v0.1 | Adversarial review | **Revise — not publication-ready.** The narrow normative claim survives; the framework claim does not |
| [`04-constitution-not-cage/self_red_team_v0.2.md`](04-constitution-not-cage/self_red_team_v0.2.md) | v0.2 | Author's same-model self-red-team | Explicitly framed as a floor, not a substitute for external review |
| [`04-constitution-not-cage/round2_adversarial_review_v0.2.md`](04-constitution-not-cage/round2_adversarial_review_v0.2.md) | v0.2 | Round-two adversarial review (regression table) | **Revise** — *"substantially better and still not publication-ready"* |
| [`04-constitution-not-cage/final_publication_gate_review.md`](04-constitution-not-cage/final_publication_gate_review.md) | final draft | Final adversarial / publication-gate review | **Conditional pass** after surgical corrections; no further conceptual rewrite required |

Note that the self-red-team document is the author reviewing his own draft with the same model that helped write it. It is included for completeness and is the weakest evidence in this directory; it is labelled as such in its own text.

### V. *The Peership Thesis* (v1.0 deposited) — and its one-page companion

The four-round chain, concluding **14 July 2026** with a **PASS**.

| Document | Type | Outcome |
|---|---|---|
| [`05-peership-thesis/round1_canonical_adversarial_review.md`](05-peership-thesis/round1_canonical_adversarial_review.md) | Full hostile review (r1.1) | **FAIL** |
| [`05-peership-thesis/round2_adversarial_rereview.md`](05-peership-thesis/round2_adversarial_rereview.md) | Draft-2 re-review | Conditional pass on the argument |
| [`05-peership-thesis/round3_gate_confirmation_review.md`](05-peership-thesis/round3_gate_confirmation_review.md) | Draft-3 gate confirmation | Argument gate cleared; five narrow corrections outstanding |
| [`05-peership-thesis/round3_final_gate_receipt.md`](05-peership-thesis/round3_final_gate_receipt.md) | Receipt; the five corrections restated | — |
| [`05-peership-thesis/round4_final_release_review.md`](05-peership-thesis/round4_final_release_review.md) | Draft-4 final release review | **PASS** |
| [`05-peership-thesis/gate_dispositions.md`](05-peership-thesis/gate_dispositions.md) | Dispositions against the draft-2 gate | — |
| [`05-peership-thesis/post_gate_changes.md`](05-peership-thesis/post_gate_changes.md) | Dated post-gate revision provenance | — |

The most consequential correction in this chain was doctrinal: draft 1 had broadened the thesis's antecedent to "enduringly subject to a shared institutional order," which materially widened the eligible parties. The reviewer caught it; the original wording — "enduringly governed by, and without feasible exit from, a shared basic structure" — was **restored**, and the withdrawal is disclosed in the published paper. See ledger entry **CL-T4**.

## What is deliberately not here

Draft ZIPs, working packages, and raw conversation exports are **not** committed. Git history and the Zenodo deposits provide version history. If complete development packages are ever published, they will be attached to a separate GitHub Release named `development-archive` rather than added to this tree.

## Honest limits of this record

- **Most of these documents carry no date and name no reviewing model.** The prompts specify a non-Anthropic model; the review documents themselves largely do not record which model produced them, or when. This is a real weakness in the provenance, and it is recorded rather than smoothed over. Only paper V's chain is precisely dated (concluding 14 July 2026).
- **The reviews are self-administered.** The author wrote the prompts, chose the models, judged every disposition, and declared each gate cleared. Publishing the prompts (above) is what makes this auditable rather than merely asserted, but it does not make it independent.
- **A PASS here is not a credential.** It means a model, asked to attack, ran out of attacks the author judged decisive. It is not a substitute for scholarly refereeing, and the corpus does not offer it as one.
