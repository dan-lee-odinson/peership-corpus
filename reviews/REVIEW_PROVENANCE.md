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

Two notes on reading the prompts. They are **dated historical records of what a reviewer was told**, not live manifests: paper V's prompt embeds version pins and DOIs current at the handoff date, and where those disagree with [`../VERSION_MANIFEST.md`](../VERSION_MANIFEST.md), the manifest controls. And an earlier version (v1.0) of the canonical review exists but is **deliberately not committed** — the operative document is v1.1, and the whole downstream chain (the re-review, the gate confirmation, the receipt, the PASS) answers *that* text. Shipping a superseded review beside the operative one would invite a reader to audit the dispositions against the wrong document.

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

**This paper is the exception, and the asymmetry is stated rather than hidden: no adversarial-review document exists for the deposited preprint.**

The preprint was not drafted from scratch. It was derived from the ISONOMIA **whitepaper**, which had already been through an extensive development and review process of its own — the whitepaper is the reason ISONOMIA sits third in the canonical order, since its specification preceded *Constitution, Not Cage*. Because that scrutiny had already happened upstream, the review pass on the preprint itself was **short**, and it did not produce a standalone review document of the kind papers I, II, IV and V each have.

What scrutiny this paper did receive, and where it lives:

| Source of scrutiny | Where | What it is |
|---|---|---|
| The whitepaper's own development process | A working session; **not committed** | Extensive, but a chat record. Per [`../PROVENANCE.md`](../PROVENANCE.md) §6 this corpus publishes prompts, not transcripts, so it is described here rather than reproduced. |
| The living specification | [`isonomia-path-a`](https://github.com/dan-lee-odinson/isonomia-path-a) — `docs/ISONOMIA_Whitepaper_v0.6.3.md`, the Tier-1 launch spec, the simulation plan | The whitepaper and specs the preprint condenses |
| Build-time interpretive record | That repo's `DECISIONS.md` and `BLOCKERS.md` | Where the specs were ambiguous, what was decided, and what could not be resolved |
| Empirical work | That repo's `CALIBRATION.md`; a 45,000-run sweep pinned to release v1.0.0, commit `ba3ddb5`, DOI [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) | Simulation evidence |
| Citation verification | [`../reviews/corpus_verification_ledger_v1.md`](corpus_verification_ledger_v1.md) | The pre-mint verification pass covering the corpus's essays |

**None of that is a substitute for an adversarial review of the deposited paper, and it is not offered as one.** Simulation evidence in particular is not paper review: those simulations establish **sampled launch-economy behaviour only** — not constitutional legitimacy, and not a validation of Peership. See [`../implementations/isonomia.md`](../implementations/isonomia.md).

A reader comparing the five papers should know that **paper III received the least independent adversarial scrutiny as a paper**, and should weight its claims accordingly. Recording that is the point of this document.

#### The upstream review: reviews held, dispositions public

Adversarial review notes on the **ISONOMIA release package** — the whitepaper, the Tier-1 launch spec, the Path A simulation plan, and the calibration record — exist and are **held unpublished**. They are implementation-side documents: they review the specification and its evidence, not *The Isonomia Commons* as a paper. They are **not committed here** and **not published in full**, because the [`isonomia-path-a`](https://github.com/dan-lee-odinson/isonomia-path-a) repository is **frozen** until a full release is scheduled. They are marked for release at that time, with the implementation record they belong to.

**But the reviews being held does not make the upstream scrutiny unverifiable.** The *dispositions* — what the review actually changed — are already public, dated, and itemized in that repository, which is where the reader should go:

| Public record | What it evidences |
|---|---|
| [Whitepaper changelog](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Whitepaper_v0.6.3.md), v0.6 → v0.6.1 | An entry titled **"adversarial-review response"** — the review happened, and this is what it changed |
| [Launch-spec changelog](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Tier1_Launch_Spec_v0.3.4.md), nine dated entries | Itemized revisions, including the v0.3.3 → v0.3.4 **claim-discipline** pass that restated overclaims in sampled-point terms and added an explicit no-claim-about-unsampled-points qualifier |
| [`CALIBRATION.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/CALIBRATION.md) revision note | The same claim-discipline correction applied to the empirical record: "stable across the entire parameter space" → statements about the 300 sampled points only |
| [`DECISIONS.md`](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/DECISIONS.md) #35 | A spec↔code divergence caught by verification: the code was right, the spec text was wrong, and **the spec was corrected rather than the code** |

Two details worth the reader's attention, because they are the kind of thing a corpus usually hides. The claim-discipline pass was **issued as a new version (v0.3.4) rather than a silent edit to v0.3.3**, precisely because v0.3.3 is the version embedded in the deposited preprint — the historical record was preserved instead of quietly overwritten. And the sampled-point correction is an admission *against interest*: it narrows what the 45,000-run sweep is allowed to claim.

So the honest summary is: **the review documents are held; the record of what they changed is public.** A reader can verify that ISONOMIA's upstream material was adversarially reviewed and can see the corrections it produced. What they cannot yet do is read the reviews themselves and judge whether the dispositions were adequate. That remains open until the ISONOMIA release.

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
