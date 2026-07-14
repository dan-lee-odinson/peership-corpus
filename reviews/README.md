# Reviews

**REVIEW DOCUMENTS ARE NON-AUTHORITATIVE.** The frozen papers in [`../corpus/`](../corpus/) and the synchronized apparatus in [`../apparatus/`](../apparatus/) control. Where a review document and a released artifact disagree, the released artifact wins. These files are committed so that a reader can **audit** the released claims — see what was objected to, what was conceded, what was changed, and when — not because anything in them settles a question. A review is a record of a process, not a warrant.

## The method

The canonical thesis paper and its one-page companion went through **four rounds of adversarial review, concluding on 14 July 2026**. Each round was conducted by prompting a large language model to attack the draft: to look for the killing objection, to check every claimed fix against the actual text rather than against the author's summary of it, and to verify citations, metadata, and file integrity independently. Models from **different laboratories** were used across the rounds so that a single model's blind spots would be less likely to survive the whole sequence. The author (Dan Lee-Odinson) is the sole human author and the responsible party for every disposition; nothing was accepted or rejected by a model.

The sequence ran: full hostile review (FAIL) → Draft 2 re-review (conditional pass on the argument) → Draft 3 gate-confirmation pass (argument gate cleared, five narrow corrections outstanding) → Draft 4 final release review (PASS).

## The documents, in order

| File | What it is |
|---|---|
| [`canonical_adversarial_review.md`](./canonical_adversarial_review.md) | The full hostile review (revision 1.1, 13 July 2026). Reviews the whole corpus, the draft canonical paper and one-pager, the apparatus, and the `isonomia-path-a` repository. Verdict: **FAIL in its current form** — the narrower contestation claim survives, but the draft does not yet earn its stronger co-authorship conclusion. Explicitly *not* a replication of the 45,000-run sweep. |
| [`draft2_adversarial_rereview.md`](./draft2_adversarial_rereview.md) | The re-review of Draft 2 (13 July 2026). Verdict: **conditional pass on the argument; not yet release-ready as a package.** The original killing objection is cleared; the remaining issues are narrower (bridge scope, the necessity of the institutional functions, disclosure of new content), and mechanical gates — search protocol, bibliography, apparatus synchronization, DOI metadata, one-page layout — still block deposit. |
| [`draft3_gate_confirmation_review.md`](./draft3_gate_confirmation_review.md) | The short gate-confirmation pass on Draft 3 (14 July 2026), authorized by the previous round in lieu of a third full hostile review. Verdict: **conditional pass; the argument-level gate is cleared** — but five narrower corrections remain before deposit. |
| [`draft3_final_gate_receipt.md`](./draft3_final_gate_receipt.md) | The receipt on the Draft 3 review package (14 July 2026). Confirms by SHA-256 that the transferred ZIP is genuine, intact Draft 3, then restates the five outstanding gate-confirmation corrections in full (§9 aggregation language; *How to Count AIs* author order; two stale canonical-section pointers; the fork-scan claim; the DOI broken by hyphenation in the rendered one-pager). Verdict: **still conditional**, on version-order grounds rather than argument grounds. |
| [`draft4_final_release_review.md`](./draft4_final_release_review.md) | The final release review (14 July 2026). Verdict: **PASS** — all five gate items resolved, no detected regression, suitable to freeze as the canonical text. One qualification, on packaging rather than argument: the reviewed ZIP was a complete review package, not yet a complete arXiv upload package. |
| [`gate_dispositions.md`](./gate_dispositions.md) | Draft 3's dispositions against the Draft 2 gate, item by item: what was accepted and implemented in the text, what was held pending the author's approval, and what remained the author's deposit-day work (search protocols, DOI assignment, third-party metadata verification). No gate item was rejected outright; several were resolved by reclassification rather than by the fix the reviewer proposed, and the table says so. |
| [`post_gate_changes.md`](./post_gate_changes.md) | Dated post-gate revision provenance. Records the five corrections applied in Draft 4, and then a Draft 5 correction made after the PASS at the author's direction — a corpus-order metadata change (I. *Gods and Slaves* · II. *Peership* · III. *The Isonomia Commons* · IV. *Constitution, Not Cage* · V. *The Peership Thesis*) with no argumentative text altered. |

## A caveat, in the corpus's own voice

An adversarial review conducted with AI models is a **quality-control process**. That is the whole of what it is.

It is **not evidence of machine political agency**. A model asked to attack a draft and producing objections is doing textual criticism under instruction; nothing about that exercise shows that the model has interests, standing, or a claim to membership in anything. The corpus does not claim that present AI systems are conscious, persons, or peers, and it would be a self-serving misreading to treat its own production process as evidence for its subject matter. If anything, the reviews were used *because* their output could be checked line by line against primary sources by a human who remained responsible for every decision.

It is also **not peer review in the scholarly sense**. No independent scholar refereed these works. No journal or programme committee has evaluated them. There was no editor, no anonymity, no disciplinary community exercising judgment, and no possibility of the author being told "no" by anyone with standing to enforce it. **These are preprints. They have not been peer reviewed.** Cite them accordingly.

## What is not committed here

Draft ZIPs, working packages, and raw conversation exports are **deliberately not committed**. The review documents refer to those artifacts by name and by SHA-256; the artifacts themselves are absent, and their absence is intentional rather than an oversight.

Version history is provided by the repository's git history and by the Zenodo records, which are the archival deposits. A reader who wants to know what changed and when should read those, not a pile of intermediate ZIPs.

If complete development packages are ever published, they will be attached to a separate GitHub Release named **`development-archive`**, and will not be added to the main tree.
