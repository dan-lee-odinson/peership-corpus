# Reviews

The adversarial-review record for the corpus, organized per paper.

**Start with [`REVIEW_PROVENANCE.md`](REVIEW_PROVENANCE.md)** — it is the index, and it states what each paper's cycle actually covered, what the verdicts were, and where the record is incomplete.

## Read this before you read anything else here

**REVIEW DOCUMENTS ARE NON-AUTHORITATIVE.** The frozen papers in [`../corpus/`](../corpus/) and the synchronized apparatus in [`../apparatus/`](../apparatus/) control. Where a review document and a released artifact disagree, the released artifact wins. These files are committed so that a reader can **audit** the released claims — see what was objected to, what was conceded, what was changed, and when — not because anything in them settles a question. A review is a record of a process, not a warrant.

**Each paper ran its own review cycle.** There is no single review of the corpus as a whole. The four-round chain that concluded on 14 July 2026 with a PASS belongs to **paper V**, *The Peership Thesis*. It is not a credential for papers I–IV, which cleared their own earlier gates, and it must not be cited as though the whole corpus passed one review.

**This is not peer review.** No journal, no editor, no independent human referee. The reviews were produced by prompting large language models — drawn from different laboratories than the model used in drafting — to attack the drafts. That is quality control. The papers are preprints and have not been peer reviewed. The author (Dan Lee-Odinson) is the sole human author and the responsible party for every disposition; nothing was accepted or rejected by a model.

**Nothing here is evidence of machine political agency.** A model that produces a sharp objection has produced text. A corpus that argues about the conditions of machine political membership has to be scrupulous about this, because the cheat would be obvious and fatal. See [`../PROVENANCE.md`](../PROVENANCE.md) §3.1.

## Layout

| Directory | Paper | Records |
|---|---|---|
| [`01-gods-and-slaves/`](01-gods-and-slaves/) | I. *Gods and Slaves* | 2 — the adversarial cross-essay review of v1.1, and the disposition record showing what v1.2 changed in response |
| [`02-peership/`](02-peership/) | II. *Peership* | 14 — including **both review prompts**, the round-1 review that **failed** the draft, five integration/confirmation audits, two disposition records, and the final-round gate |
| — | III. *The Isonomia Commons* | **No adversarial-review document exists for the deposited preprint.** It was derived from the ISONOMIA whitepaper, which had already been reviewed extensively upstream, so the preprint pass was short. The asymmetry is stated, not hidden — see [`REVIEW_PROVENANCE.md`](REVIEW_PROVENANCE.md). |
| [`04-constitution-not-cage/`](04-constitution-not-cage/) | IV. *Constitution, Not Cage* | 5 — two adversarial rounds, a self-red-team, the publication gate, and a 41-patch disposition log |
| [`05-peership-thesis/`](05-peership-thesis/) | V. *The Peership Thesis* | 7 — the four-round chain, the gate dispositions, and post-gate provenance |
| [`corpus_verification_ledger_v1.md`](corpus_verification_ledger_v1.md) | Corpus-wide | The pre-mint citation-verification ledger — the document that **blocked the DOI mints** until every claim was pinned to a primary source |

Each paper's record now has **both halves**: the reviews (what was objected to) and the dispositions (what the author actually changed, and what he declined). A review alone shows what a critic said; a disposition shows what was conceded.

## The prompts are published

[`02-peership/PROMPT_round1_adversarial_review.md`](02-peership/PROMPT_round1_adversarial_review.md) and [`02-peership/PROMPT_round2_integration_audit.md`](02-peership/PROMPT_round2_integration_audit.md) are committed deliberately.

A self-administered adversarial review invites one obvious objection: how does anyone know the reviewer was told to attack rather than to bless? The prompts answer it. Read them and judge for yourself what was demanded — the round-1 prompt asks for the killing objection, a citation hit-list, an AI-tell hit-list, and "the objection I could not answer," and directs the draft to a model from a different lineage than the one that wrote it.

Prompts are published; **chat transcripts are not**. See [`../PROVENANCE.md`](../PROVENANCE.md) §6 for why the line is drawn there.

## What the reviews cost the corpus

These are not favourable documents, and they were not selected to flatter.

The round-1 review of *Peership* v0.4 returned **FAIL** and killed the draft's central claim — that Peership was the *uniquely* coherent stance, invariant under the power ratio. That exclusivity argument does not appear in the published paper. What survived is the narrower distinction between welfare and constitutional standing, which is why the corpus now insists that welfare protection is a floor and not Peership.

The chain for paper V forced a doctrinal restoration: draft 1 had quietly broadened the thesis's antecedent to "enduringly subject to a shared institutional order," materially widening the eligible parties. The reviewer caught it, the original wording was restored, and the withdrawal is disclosed in the published paper (ledger **CL-T4**).

## Not committed

Draft ZIPs, working packages, and raw conversation exports are deliberately excluded. Git history and the Zenodo deposits provide version history. Complete development packages, if ever published, would be attached to a separate GitHub Release named `development-archive`.
