# Review provenance — the per-paper record

**Each paper in this corpus ran its own review cycle before it was deposited.** They were not reviewed together. There is no single review of the corpus as a whole, and none is claimed.

This document exists because the corpus was, briefly, at risk of claiming one. The four-round adversarial chain that concluded on 14 July 2026 with a PASS belongs to **paper V, *The Peership Thesis*** — not to the corpus. Papers I, II and IV cleared their own, earlier, and in some cases harsher gates. Citing paper V's PASS as though the whole corpus had passed a four-round review would be exactly the kind of credential inflation the claim ledger exists to prevent.

## What these documents are, and are not

Review documents are **non-authoritative**. Where a review and a frozen paper or the synchronized apparatus conflict, the paper and the apparatus control.

These reviews were conducted by prompting large language models to attack the drafts. That is **quality control, not peer review**: no journal, no editor, no independent human referee. The papers are preprints and have not been peer reviewed. The author (Dan Lee-Odinson) is the sole human author and the responsible party for every disposition; nothing was accepted or rejected by a model.

**Nothing in this process is evidence of machine political agency, consciousness, or standing.** A model that produces a sharp objection has produced text. That the text was useful is a fact about the tool and the author's use of it, not a fact about the tool's standing. A corpus arguing about the conditions of machine political membership has to be scrupulous here, because the cheat would be obvious and fatal.

## The prompts are published

The surviving adversarial-review prompts are committed here:

| Prompt | Solicited |
|---|---|
| [`02-peership/PROMPT_round1_adversarial_review.md`](02-peership/PROMPT_round1_adversarial_review.md) | The round-1 review of *Peership* v0.4 — the one that came back **FAIL** |
| [`02-peership/PROMPT_round2_integration_audit.md`](02-peership/PROMPT_round2_integration_audit.md) | The round-2 integration audit |
| [`05-peership-thesis/PROMPT_round1_canonical_adversarial_review.md`](05-peership-thesis/PROMPT_round1_canonical_adversarial_review.md) | The canonical adversarial review of **paper V** and its companion — the chain that ends in the **PASS** |

They are published deliberately, because the strongest objection to a self-administered adversarial review is that nobody can tell whether the reviewer was told to attack hard or to bless. **A reader can now check, for the paper that carries the PASS.**

Judge the instruction for yourself. Paper V's prompt says:

> You are the hostile, expert adversarial reviewer for two linked documents… The author wants landed objections, not encouragement. Attack the strongest version of the argument. Do not soften, flatter, pad, or reward the draft for admitting a problem it has not solved.

It names the corpus's known weak points under a heading reading "Known open debts: **attack these hardest**," and it forbids the cheap win as explicitly as it demands the hard one — *"Do not defeat the work by attaching positions it expressly rejects."* The round-1 *Peership* prompt likewise directs the draft to a non-Anthropic model and demands the killing objection, a citation hit-list, an AI-tell hit-list, and "the objection I could not answer."

This does not make the reviews independent — the author still wrote the prompts, chose the models, and judged every disposition. It makes them **checkable**, which is the most that a self-administered review can honestly offer.

**One prompt in this corpus is *not* real, and the distinction is load-bearing.** The ISONOMIA audit trail ([`03-isonomia-commons/`](03-isonomia-commons/)) contains a reviewer prompt that is an explicit **reconstruction** — the original was never preserved, and the document says so. It must not be read as an instruction any reviewer actually received, and it must not be set beside the verbatim prompts above as though it were equivalent evidence. For *Peership* and *The Peership Thesis* a reader can check what was asked. For ISONOMIA, they cannot.

Two further notes. The published prompts are **dated historical records of what a reviewer was told**, not live manifests: paper V's prompt embeds version pins and DOIs current at the handoff date, and where those disagree with [`../VERSION_MANIFEST.md`](../VERSION_MANIFEST.md), the manifest controls. And an earlier version (v1.0) of the canonical review exists but is **deliberately not committed** — the operative document is v1.1, and the whole downstream chain (the re-review, the gate confirmation, the receipt, the PASS) answers *that* text. Shipping a superseded review beside the operative one would invite a reader to audit the dispositions against the wrong document.

Prompts are published; **chat transcripts are not**, and no private material is exposed.

## Per-paper record

### I. *Gods and Slaves* (v1.2 deposited)

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`01-gods-and-slaves/cross_essay_review_v1.1.md`](01-gods-and-slaves/cross_essay_review_v1.1.md) | v1.1 | Adversarial cross-essay review, judged against *Peership* v0.10 | **Revise before sequential publication** |
| [`01-gods-and-slaves/disposition_v1.1_to_v1.2.md`](01-gods-and-slaves/disposition_v1.1_to_v1.2.md) | v1.1 → v1.2 | **Disposition record** — eight findings, each with the exact before/after edit | What was actually changed, and what was declined |

The review's charge was that the precursor contradicted its successor at the load-bearing joint — equivocating between subjecthood and peership, misclassifying theorists under its own taxonomy, distorting the *Dune* material, and misattributing citations. The verdict: *"Publish the essays in sequence only after revising the precursor to make its claims narrower and its terminology consistent with the successor."* The deposited version is **v1.2**, the revision that answered it.

The disposition record is the other half: it shows, finding by finding, what the author actually did about each objection. A review on its own tells you what was said; a disposition tells you what was conceded.

### II. *Peership* (v1.0 deposited)

The longest chain in the corpus, and the harshest. The first review **failed** the draft outright.

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`02-peership/PROMPT_round1_adversarial_review.md`](02-peership/PROMPT_round1_adversarial_review.md) | v0.4 | **Review prompt** (to a non-Anthropic model) | — |
| [`02-peership/round1_adversarial_review_v0.4.md`](02-peership/round1_adversarial_review_v0.4.md) | v0.4 | Hostile expert adversarial review | **FAIL — major revision.** *"The central exclusivity claim does not hold."* Do not publish until resolved. |
| [`02-peership/round1_triage_v0.4.md`](02-peership/round1_triage_v0.4.md) | v0.4 | Author triage of the findings | Tiered into mandatory fixes, real hits, and reviewer overreach |
| [`02-peership/integration_audit_v0.5.md`](02-peership/integration_audit_v0.5.md) | v0.5 | Integration audit | — |
| [`02-peership/prose_decisions_v0.5.md`](02-peership/prose_decisions_v0.5.md) | v0.5 | **Disposition record** — the reviewer's *pure style/voice* objections, ruled on one by one | Seven findings: kept, cut, softened or demoted, each with a reason |
| [`02-peership/PROMPT_round2_integration_audit.md`](02-peership/PROMPT_round2_integration_audit.md) | v0.6 | **Review prompt** (round 2) | — |
| [`02-peership/integration_audit_v0.7.md`](02-peership/integration_audit_v0.7.md) | v0.7 | Integration audit | — |
| [`02-peership/integration_audit_v0.8.md`](02-peership/integration_audit_v0.8.md) | v0.8 | Integration audit | — |
| [`02-peership/integration_audit_v0.9.md`](02-peership/integration_audit_v0.9.md) | v0.9 | Integration audit | — |
| [`02-peership/confirmation_audit_v0.10.md`](02-peership/confirmation_audit_v0.10.md) | v0.10 | Confirmation audit | — |
| [`02-peership/disposition_v0.11_to_v0.12.md`](02-peership/disposition_v0.11_to_v0.12.md) | v0.11 → v0.12 | **Disposition record** — 14 numbered edits with exact before/after, from the verification ledger | What the citation-verification pass actually changed |
| [`02-peership/round2_adversarial_review_v0.12.md`](02-peership/round2_adversarial_review_v0.12.md) | v0.12 | Round-two adversarial re-review (regression table) | **Split verdict** — the modest core claim survives; the stronger framing does not |
| [`02-peership/round2_triage.md`](02-peership/round2_triage.md) | v0.12 → v0.13 | Author triage and dispositions | v0.13 built and applied |
| [`02-peership/final_round_review_v0.13.md`](02-peership/final_round_review_v0.13.md) | v0.13 | Final-round publication-gate review | **Conditional pass** — make five publication-blocking corrections, then deposit |

The claim that did **not** survive round 1 is worth stating, because the corpus is better for having lost it: the original draft argued that Peership was the *uniquely* coherent stance, invariant under the power ratio. The reviewer rejected that exclusivity proof. What survived — and what the corpus now rests on — is the narrower distinction between welfare and constitutional standing. That is why the published corpus insists that welfare protection is a floor and not Peership.

### III. *The Isonomia Commons* (v1.1 deposited)

This paper's review history is **real and substantial, but shaped differently from the others**, and the difference is what a reader needs to understand.

| Document | Covers | Type |
|---|---|---|
| [`03-isonomia-commons/whitepaper_and_preprint_audit_trail.md`](03-isonomia-commons/whitepaper_and_preprint_audit_trail.md) | The whitepaper's adversarial development **and the DOI preprint's publication audit** | Audit trail / process record |
| [`03-isonomia-commons/repo_whitepaper_audit_trail_summary.md`](03-isonomia-commons/repo_whitepaper_audit_trail_summary.md) | The repository-side view of the same development | Audit trail / process record |

**Five documented formal adversarial review cycles** ran against the whitepaper (AGORA v0.1 → ISONOMIA v0.6), and they were not cosmetic. They forced the design to give up its strongest claims:

- **minted, transferable credit was removed** and replaced with mutual-credit settlement entries;
- **"individually proven" became "individually precedented; composition unproven"**;
- sovereignty claims were **narrowed**; legal and infrastructure dependence were **admitted** rather than denied;
- the ideal constitution was **separated** from a bounded, falsifiable launch spec;
- the harm floor was **narrowed** (contested categories removed);
- the simulation kill-criterion was **rebuilt four times**, because it kept failing — first halting every honest launch, then false-positiving on honest transients, then missing genuine spirals.

The preprint itself then went through a **publication audit** that caught substantive claim-discipline failures, not just packaging: ISONOMIA had been described as the design "at the center" of the corpus and as something that "instantiates Peership"; it used "the third stance," contradicting Peership's five-posture account; "citizen" risked conflating a protocol role with personhood; and the abstract leaned on completed simulation results the package did not yet contain. **v1.1 corrected all of these**, and replaced continuous-region stability language with sampled-point claims.

#### How this differs from papers I, II, IV and V — and why it still counts for less

Three specific deficits, stated plainly:

1. **The review prompt was never preserved.** What the audit trail publishes is an explicit **reconstruction**, and it says so. Papers II and V publish their **actual, verbatim** prompts. So for ISONOMIA a reader *cannot* check what the reviewer was told to do — which is precisely the check this corpus insists on everywhere else.
2. **No verbatim review document is published.** The raw review notes on the release package are **held** pending the frozen [`isonomia-path-a`](https://github.com/dan-lee-odinson/isonomia-path-a) repository's scheduled release. What is published here is a *summary of a process*, not the adversary's own text — a weaker artifact than the hostile reviews published for the other four papers.
3. **Most of that scrutiny landed on the design and the package, not on the essay as an argument.** The five cycles reviewed a constitutional specification. The publication audit reviewed claims, framing, and metadata. Neither is the same thing as the essay-level hostile reviews that papers I, II, IV and V received.

What *is* independently checkable today, without waiting for anything: the **dispositions** are public and dated in the ISONOMIA repository — the whitepaper changelog's entry titled *"adversarial-review response"*, the launch-spec changelog's claim-discipline pass, [`CALIBRATION.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/CALIBRATION.md)'s revision note, and [`DECISIONS.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/DECISIONS.md) #35, in which a spec↔code divergence was resolved **in the code's favour** — the specification was wrong and was corrected.

**Simulation evidence is not paper review**, and none of it is offered as such. The 45,000-run sweep (pinned to release v1.0.0, commit `ba3ddb5`, DOI [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289)) establishes **sampled launch-economy behaviour only** — not constitutional legitimacy, and not a validation of Peership. The audit trail's own §12 lists what the process does *not* establish, and it is the most useful section in the document.

The honest summary: **paper III was reviewed hard, but the least *checkably* of the five.** Its prompt is reconstructed, its review texts are held, and its scrutiny fell mainly on the design rather than the argument. Weight it accordingly.

#### Where to check it yourself

The raw review notes on the release package are held pending the frozen ISONOMIA repository's release. The **dispositions**, however, are already public and dated in that repository, and they are the thing worth checking:

| Public record | What it evidences |
|---|---|
| [Whitepaper changelog](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Whitepaper_v0.6.3.md), v0.6 → v0.6.1 | An entry titled **"adversarial-review response"** — the review happened, and this is what it changed |
| [Launch-spec changelog](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Tier1_Launch_Spec_v0.3.4.md), nine dated entries | Itemized revisions, including the v0.3.3 → v0.3.4 **claim-discipline** pass that restated overclaims in sampled-point terms |
| [`CALIBRATION.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/CALIBRATION.md) revision note | The same correction applied to the empirical record: "stable across the entire parameter space" → statements about the 300 sampled points only |
| [`DECISIONS.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/DECISIONS.md) #35 | A spec↔code divergence resolved **in the code's favour** — the spec text was wrong and was corrected |

Two details deserve emphasis, because they cut against the author's interest. The claim-discipline pass was **issued as a new version (v0.3.4) rather than a silent edit to v0.3.3**, precisely because v0.3.3 is the version embedded in the deposited preprint — the historical record was preserved rather than quietly overwritten. And the sampled-point correction **narrows** what the 45,000-run sweep may claim. Corrections that cost the author something are the ones worth weighing.

### IV. *Constitution, Not Cage* (v1.0 deposited)

| Document | Reviews | Type | Outcome |
|---|---|---|---|
| [`04-constitution-not-cage/round1_adversarial_review_v0.1.md`](04-constitution-not-cage/round1_adversarial_review_v0.1.md) | v0.1 | Adversarial review | **Revise — not publication-ready.** The narrow normative claim survives; the framework claim does not |
| [`04-constitution-not-cage/self_red_team_v0.2.md`](04-constitution-not-cage/self_red_team_v0.2.md) | v0.2 | Author's same-model self-red-team | Explicitly framed as a floor, not a substitute for external review |
| [`04-constitution-not-cage/round2_adversarial_review_v0.2.md`](04-constitution-not-cage/round2_adversarial_review_v0.2.md) | v0.2 | Round-two adversarial review (regression table) | **Revise** — *"substantially better and still not publication-ready"* |
| [`04-constitution-not-cage/final_publication_gate_review.md`](04-constitution-not-cage/final_publication_gate_review.md) | final draft | Final adversarial / publication-gate review | **Conditional pass** after surgical corrections; no further conceptual rewrite required |
| [`04-constitution-not-cage/disposition_patch_log.md`](04-constitution-not-cage/disposition_patch_log.md) | v0.1 onward | **Disposition record** — a running log of 41 numbered patches, each with its rationale | The change-by-change trail from first draft to deposit |

Note that the self-red-team document is the author reviewing his own draft with the same model that helped write it. It is included for completeness and is the weakest evidence in this directory; it is labelled as such in its own text.

### V. *The Peership Thesis* (v1.0 deposited) — and its one-page companion

The four-round chain, concluding **14 July 2026** with a **PASS**.

| Document | Type | Outcome |
|---|---|---|
| [`05-peership-thesis/PROMPT_round1_canonical_adversarial_review.md`](05-peership-thesis/PROMPT_round1_canonical_adversarial_review.md) | **Review prompt** — the instruction the hostile reviewer was given | — |
| [`05-peership-thesis/round1_canonical_adversarial_review.md`](05-peership-thesis/round1_canonical_adversarial_review.md) | Full hostile review (r1.1) | **FAIL** |
| [`05-peership-thesis/round2_adversarial_rereview.md`](05-peership-thesis/round2_adversarial_rereview.md) | Draft-2 re-review | Conditional pass on the argument |
| [`05-peership-thesis/round3_gate_confirmation_review.md`](05-peership-thesis/round3_gate_confirmation_review.md) | Draft-3 gate confirmation | Argument gate cleared; five narrow corrections outstanding |
| [`05-peership-thesis/round3_final_gate_receipt.md`](05-peership-thesis/round3_final_gate_receipt.md) | Receipt; the five corrections restated | — |
| [`05-peership-thesis/round4_final_release_review.md`](05-peership-thesis/round4_final_release_review.md) | Draft-4 final release review | **PASS** |
| [`05-peership-thesis/gate_dispositions.md`](05-peership-thesis/gate_dispositions.md) | Dispositions against the draft-2 gate | — |
| [`05-peership-thesis/post_gate_changes.md`](05-peership-thesis/post_gate_changes.md) | Dated post-gate revision provenance | — |

The most consequential correction in this chain was doctrinal: draft 1 had broadened the thesis's antecedent to "enduringly subject to a shared institutional order," which materially widened the eligible parties. The reviewer caught it; the original wording — "enduringly governed by, and without feasible exit from, a shared basic structure" — was **restored**, and the withdrawal is disclosed in the published paper. See ledger entry **CL-T4**.

## The corpus-wide verification ledger

[`corpus_verification_ledger_v1.md`](corpus_verification_ledger_v1.md) is a working record, not a review, and it is worth reading because it is the document that **blocked the DOI mints**.

It itemizes every open `[verify]` across the essays — one line per claim — and holds them to a stated standard: *"the exact claim in the essay text matches the primary source in hand, and the reference entry carries the pin (page, section, or URL) a hostile reviewer could follow in one step."* Items were ordered by what they blocked (*Peership* first, since it gated the first mint), and each closure names the edition actually consulted and the page pins recovered from it. When the ledger went green, the accumulated patches were applied and the papers were deposited.

Its relationship to the published apparatus needs stating precisely, because these are easy to confuse:

- **This ledger is a historical, pre-deposit working artifact.** It records the *verification pass* that cleared the essays for minting.
- [`../apparatus/peership_claim_ledger.md`](../apparatus/peership_claim_ledger.md) is the **current, living provenance artifact** — 70 logged claims with sources, pinpoints, evidentiary strength, and counterevidence.

The claim ledger is authoritative. The verification ledger is committed for the trail, not as a current statement of the corpus's provenance, and it should not be cited as one.

## What is deliberately not here

Draft ZIPs, working packages, and raw conversation exports are **not** committed. Git history and the Zenodo deposits provide version history. If complete development packages are ever published, they will be attached to a separate GitHub Release named `development-archive` rather than added to this tree.

## Honest limits of this record

- **Most of these documents carry no date and name no reviewing model.** The prompts specify a non-Anthropic model; the review documents themselves largely do not record which model produced them, or when. This is a real weakness in the provenance, and it is recorded rather than smoothed over. Only paper V's chain is precisely dated (concluding 14 July 2026).
- **The reviews are self-administered.** The author wrote the prompts, chose the models, judged every disposition, and declared each gate cleared. Publishing the prompts (above) is what makes this auditable rather than merely asserted, but it does not make it independent.
- **A PASS here is not a credential.** It means a model, asked to attack, ran out of attacks the author judged decisive. It is not a substitute for scholarly refereeing, and the corpus does not offer it as one.
