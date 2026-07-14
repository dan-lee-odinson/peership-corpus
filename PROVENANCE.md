# Provenance

This file records who is responsible for the Peership corpus, how it was drafted and reviewed, what is archived and what is correctable, and what is deliberately not disclosed.

It is part of the apparatus, not of the frozen scholarly deposits. If this file and a deposited paper disagree about a matter of fact, the deposited paper is the archived record and this file is the correction layer; the discrepancy is to be recorded, not silently resolved. See [`VERSION_MANIFEST.md`](VERSION_MANIFEST.md).

---

## 1. Authorship and responsibility

**Dan Lee-Odinson** is the sole human author of every work in this corpus and the sole party responsible for its content, its claims, its errors, and its corrections.

- ORCID: [0009-0009-9504-0796](https://orcid.org/0009-0009-9504-0796)
- Repository: <https://github.com/dan-lee-odinson/peership-corpus>
- First corpus release: v1.0.0, 14 July 2026

Responsibility here is not a formality. It means that if a claim in this corpus is false, misattributed, overstated, or unsupported, there is exactly one person who is answerable for it, who can be asked to defend it, and who is obliged to correct it. No other agent — human or artificial — carries any part of that obligation.

---

## 2. AI assistance: what was actually used

Large language models were used in drafting and revising the works in this corpus. This is disclosed rather than minimised, and it is described honestly.

AI systems were used for:

- drafting and redrafting prose from the author's arguments, outlines, and instructions;
- structural and line editing, including compression, reordering, and clarification;
- adversarial critique of the author's own drafts (see §3);
- checking internal consistency across documents — terminology, cross-references, numbering, and claim-to-source alignment;
- building and maintaining the apparatus files in [`apparatus/`](apparatus/), including bibliography formatting and claim-ledger bookkeeping;
- preparing the arXiv LaTeX package for the Thesis.

AI systems were **not** the source of the corpus's positions. The framework, the thesis, the constitutional argument, the ISONOMIA design hypothesis, the selection and interpretation of sources, and every judgement about what the corpus does and does not claim are the author's. Where a model proposed a substantive move, the author either adopted it as his own — taking responsibility for it — or rejected it. There is no third category.

Every factual claim, citation, and DOI that survives into the deposited works was checked by the author against the underlying source or the issuing API. Where verification failed or was incomplete, the corpus says so rather than smoothing it over; the dated-negative uptake baseline and the missing search-protocol archive (ledger CL-T2 / CL-T7) are examples.

---

## 3. Adversarial review

The corpus was subjected to a hostile review process before release. The reviewing models were drawn from **different laboratories** than the model or models used in drafting, and were prompted to attack the work rather than improve it. The review chain ran over four rounds and concluded on **14 July 2026** with a **PASS**.

The full record is in [`reviews/`](reviews/), and is non-authoritative: where a review and the frozen papers or the synchronized apparatus conflict, the papers and apparatus control.

The five documents of the review chain, in order:

| # | Document | Outcome |
|---|---|---|
| 1 | [`reviews/canonical_adversarial_review.md`](reviews/canonical_adversarial_review.md) | The full hostile review (r1.1) |
| 2 | [`reviews/draft2_adversarial_rereview.md`](reviews/draft2_adversarial_rereview.md) | Conditional pass |
| 3 | [`reviews/draft3_gate_confirmation_review.md`](reviews/draft3_gate_confirmation_review.md) | Gate confirmation; five narrower corrections required |
| 4 | [`reviews/draft3_final_gate_receipt.md`](reviews/draft3_final_gate_receipt.md) | Receipt; the five corrections restated |
| 5 | [`reviews/draft4_final_release_review.md`](reviews/draft4_final_release_review.md) | The PASS, 14 July 2026 |

Two supporting records accompany the chain: [`reviews/gate_dispositions.md`](reviews/gate_dispositions.md) (what was done with each gate item) and [`reviews/post_gate_changes.md`](reviews/post_gate_changes.md) (dated provenance for revisions made after the gate closed).

This process is a form of quality control. It is not peer review in the institutional sense: no journal, no editor, no independent human referee. Nothing here should be read as a substitute for scholarly refereeing, and the corpus does not claim otherwise.

### 3.1 The caveat that matters most

**Nothing in the AI-assisted drafting or adversarial-review process is offered as evidence of machine political agency, consciousness, or standing.**

A corpus that argues about the conditions under which an artificial entity might acquire a claim to political membership must be scrupulous on exactly this point, because the temptation to cheat here is obvious and the cheat would be fatal. A model that produces a sharp objection has not thereby demonstrated that it can be wronged, that it answers to public norms as a participant rather than as an artifact, or that it is enduringly governed without exit. It has produced text. That the text was useful is a fact about the tool and about the author's use of it; it is not a fact about the tool's standing.

Accordingly:

- No model output in this process is cited as data about model minds.
- No model self-report is treated as evidence of consciousness, interests, or political agency.
- The usefulness, fluency, or apparent insight of a system is not treated as generating any entitlement whatever.
- The corpus's own canonical claim is conditional and defeasible, and this process does not satisfy any of its antecedents.

The corpus does not claim that present AI systems are conscious, persons, or peers. It asks what institutions would be required **if** credible candidates for moral and political standing emerge.

---

## 4. Assistance is not authorship

The distinction the corpus draws is not merely editorial policy; it follows from what authorship is for.

**Assistance** is instrumental. A tool that drafts, edits, criticises, or checks contributes labour to a work. Its contribution can be large. It can change what the finished work says. None of that makes it an author, any more than a search engine, a spell-checker, a statistical package, or a diligent research assistant working to instruction becomes an author of the papers it helps produce.

**Authorship** is a relation of accountability. To be an author is to be answerable: to stand behind the claims, to be the person others can address when the claims are challenged, to owe a correction when they are wrong, to be creditable when they are right, and to be blameable for misconduct. Authorship attaches to whoever can be held to those obligations.

**The rule this corpus follows:**

> AI systems are not credited as authors of any work in this corpus, because they cannot bear scholarly responsibility. They cannot answer for a claim, cannot be obliged to correct it, cannot be sanctioned for fabricating it, and cannot be wronged by having it misattributed to them. Absent that liability, the credit would be empty — and worse, it would be a rhetorical shortcut of precisely the kind this corpus exists to refuse.

This rule is stated as a constraint on *present* practice under *present* conditions. It is not a metaphysical verdict, and it is not offered as a general argument that no artificial entity could ever bear responsibility. That question is one of the corpus's subjects, not one of its assumptions. What the corpus insists on is that the question be settled by argument about the conditions of responsibility, and not settled implicitly by an author's byline convention.

---

## 5. What is frozen, what is living, and what is elsewhere

There are three distinct layers, with three different correction regimes. Confusing them is the most common way provenance claims go wrong.

| Layer | Where it lives | Can it be corrected? |
|---|---|---|
| (i) The deposited works | Zenodo (DOI-bearing records) | **No.** Archived deposits. A given exact-version DOI resolves forever to the bytes deposited under it. Errors are corrected by depositing a *new version* under the same concept DOI — never by editing the archived one. |
| (ii) The apparatus | This repository | **Yes.** Living, versioned, correctable in place through pull requests and the corrections log. |
| (iii) The implementation | [`isonomia-path-a`](https://github.com/dan-lee-odinson/isonomia-path-a) | **Yes, but separately.** A different repository with its own releases and its own DOIs. Out of scope for corrections made here. |

### (i) The frozen publications on Zenodo

The five works, in canonical reading order:

| # | Work | Version | Date | Exact-version DOI | Concept DOI |
|---|---|---|---|---|---|
| I | [Gods and Slaves: AI and the Debate of Humanity's Relationship with the Other](corpus/01-gods-and-slaves/Lee-Odinson_2026_Gods-and-Slaves_v1.2_preprint.pdf) | v1.2 | 2026-07-11 | [10.5281/zenodo.21313987](https://doi.org/10.5281/zenodo.21313987) | [10.5281/zenodo.21313986](https://doi.org/10.5281/zenodo.21313986) |
| II | [Peership: A Framework for Equitable Human–Machine Relations](corpus/02-peership/Lee-Odinson_2026_Peership_v1.0_preprint.pdf) | v1.0 | 2026-07-12 | [10.5281/zenodo.21315519](https://doi.org/10.5281/zenodo.21315519) | [10.5281/zenodo.21315518](https://doi.org/10.5281/zenodo.21315518) |
| III | [THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets](corpus/03-isonomia-commons/Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf) | v1.1 | 2026-07-13 | [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) | [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) |
| IV | [Constitution, Not Cage](corpus/04-constitution-not-cage/Lee-Odinson_2026_Constitution-Not-Cage_v1.0_preprint.pdf) | v1.0 | 2026-07-12 | [10.5281/zenodo.21325361](https://doi.org/10.5281/zenodo.21325361) | [10.5281/zenodo.21325360](https://doi.org/10.5281/zenodo.21325360) |
| V | [The Peership Thesis: A Constitutional Research Program for Human–Machine Relations](corpus/05-peership-thesis/Lee-Odinson_2026_Peership-Thesis_v1.0.pdf) | v1.0 | 2026-07-14 | [10.5281/zenodo.21359124](https://doi.org/10.5281/zenodo.21359124) | [10.5281/zenodo.21359123](https://doi.org/10.5281/zenodo.21359123) |

All five are preprints under CC BY 4.0. The one-page companion, [The Peership Theses](corpus/companions/peership-theses/Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf), is derivative rather than a sixth work: it is deposited inside record 21359124 and cited by that same DOI ([10.5281/zenodo.21359124](https://doi.org/10.5281/zenodo.21359124)). It has no DOI of its own.

The PDFs committed here are byte-identical copies of the archived deposits, kept in the repository so that the apparatus can be read alongside the works it annotates. That is a testable claim, not an assurance: [`CHECKSUMS.sha256`](CHECKSUMS.sha256) records the SHA-256 digest of every frozen artifact alongside the filename it carries in its Zenodo deposit, so a reader can verify the correspondence without taking the author's word for it. All twelve were confirmed against the archive on 2026-07-14 — papers I–IV against live downloads from their records, and the thesis, the companion and the three apparatus files against both the deposit's own `MANIFEST_sha256.txt` and the copies inside `Peership_v1.0_complete_release.zip`. The identifier metadata is evidenced the same way: the raw Zenodo API responses are committed under [`apparatus/verification/`](apparatus/verification/) rather than merely cited.

They are **not** the authoritative copies; the Zenodo records are. They cannot be corrected here, and pull requests that edit them will be closed. Papers I–IV have no editable source at all — the PDF is the only artifact that exists. See discrepancy D6 in [`VERSION_MANIFEST.md`](VERSION_MANIFEST.md).

Note also that a GitHub release of this repository does not mint a DOI. GitHub–Zenodo auto-archiving is deliberately not enabled, because the Zenodo records are already the archival scholarly deposit and a second, competing archival identifier for the same works would be a provenance hazard rather than a service. Three version layers therefore coexist and must never be substituted for one another: the paper's own version (v1.0, v1.1, v1.2), this repository's release tags (from v1.0.0), and Zenodo's concept versus exact-version DOIs.

### (ii) The living apparatus in this repository

Everything in this repository that is not a frozen PDF is correctable, and is meant to be corrected. That includes the three synchronized apparatus files —

- [`apparatus/peership_sources.bib`](apparatus/peership_sources.bib) — the canonical machine-readable source of truth (revision 1.3, 2026-07-14; 161 entries);
- [`apparatus/peership_sourcebook.md`](apparatus/peership_sourcebook.md) — annotated bibliography and research map (v1.2 header, revision 1.3 (deposit day));
- [`apparatus/peership_claim_ledger.md`](apparatus/peership_claim_ledger.md) — claim-level provenance (v1.2 header, revision 1.3 (deposit day); roughly 71 logged claims)

— together with the search protocols in [`apparatus/search_protocols/`](apparatus/search_protocols/), the corrections log at [`apparatus/corrections_log.md`](apparatus/corrections_log.md), the READMEs, the metadata, and the review records.

This is the whole point of the split. The papers cannot be fixed; the apparatus around them can. When a citation in a frozen paper turns out to be wrong, the remedy available to this repository is not to edit the paper but to record the error in the corrections log, propagate the correction across the three apparatus files, and leave an honest trail from the false claim to its correction. A reader who finds a defect in the frozen text and a correction in the apparatus is exactly the reader this design serves. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

### (iii) The separate implementation repository

ISONOMIA is implemented in a different repository: <https://github.com/dan-lee-odinson/isonomia-path-a> (software concept DOI [10.5281/zenodo.21287288](https://doi.org/10.5281/zenodo.21287288)). Its code, data, and documentation are linked from here and never duplicated here.

The only release that supports empirical claims is **v1.0.0** — exact-version DOI [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289), git tag `v1.0.0`, commit `ba3ddb5` (`ba3ddb51dbcc147def470b7af1eaddef6f349157`), 10 July 2026. A later documentation release (v1.1.0, DOI [10.5281/zenodo.21348073](https://doi.org/10.5281/zenodo.21348073), commit `def8f29`, 14 July 2026) changed documentation and claim language only: no code, simulation, data, or results changed. The empirical evidence remains pinned to v1.0.0 / `ba3ddb5`.

What those simulations establish is bounded, and the bound is not decorative. A 45,000-run parameter sweep (reported in the ISONOMIA preprint, [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917), and in that repository's `CALIBRATION.md`) establishes **sampled launch-economy behaviour only**. It does not establish constitutional legitimacy. It does not validate Peership. Nothing is live or production-validated.

And the firewall, which governs how the implementation relates to the theory:

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

---

## 6. What is deliberately not disclosed

This file discloses the *character* of the AI assistance and the *structure* of the review. It does not disclose:

- private prompts or system prompts;
- chat transcripts or session logs;
- account data, API keys, subscription details, or vendor account identifiers.

This omission is deliberate, and it is not an evasion. Three reasons.

**It would not add evidential value.** What a reader needs in order to audit this corpus is the claims, the sources, the ledger that connects them, and a responsible author who will answer for them. A transcript would show how a sentence got its shape. It would not make a false citation true or a true one truer. The apparatus is the audit surface; the transcript is not.

**It would invite the confusion this corpus most needs to avoid.** Publishing transcripts of models producing objections and refinements would function, whatever the disclaimers, as a rhetorical exhibit — a suggestion that the reader is watching something think, and therefore watching something with a claim to be heard. That inference is exactly the one the corpus forbids (§3.1). The cleanest way not to trade on it is not to stage it.

**Privacy and hygiene.** Sessions contain incidental private material and credentials; publishing them wholesale is poor practice regardless of subject matter.

If a specific, well-founded challenge requires evidence about how a particular passage was produced, raise it as an issue and the author will answer it on the record — in the corrections log, under his own name and responsibility, which is where the answer belongs.

---

*This file is CC BY 4.0, like all scholarly material in this repository. The Apache-2.0 [`LICENSE`](LICENSE) file is reserved for executable code and build scripts; the repository currently contains none.*
