# Version manifest

Authoritative version record for the Peership corpus.

- Repository: <https://github.com/dan-lee-odinson/peership-corpus>
- Author and responsible party: Dan Lee-Odinson ([ORCID 0009-0009-9504-0796](https://orcid.org/0009-0009-9504-0796)) — sole human author
- First corpus release: **v1.0.0**, 14 July 2026
- All DOI and version metadata below was verified against the Zenodo REST API on 2026-07-14.

Where this file and any other document disagree, this file controls for version and identifier questions. Where this file and an archived Zenodo record disagree, **the archived record controls** and the disagreement is recorded in [Recorded discrepancies](#recorded-discrepancies) rather than silently repaired.

---

## Three independent version layers

Three different things in this project carry version numbers. They are independent, they advance at different times and for different reasons, and **they must never be silently substituted for one another.**

**1. Paper versions (v1.0, v1.1, v1.2 …).**
A document's own version, set by the author and printed in its front matter. It changes only when the document changes. Papers I–V are frozen preprints; their version numbers belong to them, not to this repository.

**2. GitHub corpus releases (from v1.0.0).**
This repository's release tags. A corpus release says: *these files, assembled in this arrangement, on this date.* It is a packaging and provenance event. Papers do not gain a new version because the repository is re-released, and the repository does not inherit a paper's version number.

**3. Zenodo concept DOIs vs exact-version DOIs.**
Each deposited work has a **concept DOI** (resolves to the latest version of the record — the right identifier when you mean *the work*) and an **exact-version DOI** (resolves to one immutable deposit — the right identifier when a claim depends on specific content). Empirical and evidentiary citation must use the exact-version DOI. The two are not interchangeable, and a concept DOI is not simply "the first version's DOI" (see [discrepancy D5](#recorded-discrepancies)).

**A GitHub release does NOT mint a new DOI.** GitHub–Zenodo auto-archiving is deliberately **not** enabled for this repository. The Zenodo records listed below are already the archival scholarly deposits; enabling auto-archiving would mint a second, competing identifier for the same works and create exactly the substitution this section forbids. Cite Zenodo for the works; cite the repository (by URL and release tag) for the assembly.

---

## Authoritative version table

Canonical reading order is I → V. The order is argumentative (genealogy, framework, implementation hypothesis, constraint theory, consolidation), not chronological.

| Work | Canonical role | Document version | Status | Exact-version DOI | Concept DOI | Local path | License |
|---|---|---|---|---|---|---|---|
| I. *Gods and Slaves: AI and the Debate of Humanity's Relationship with the Other* | Genealogy and literary-philosophical diagnosis of inherited human postures toward nonhuman intelligence | v1.2 (2026-07-11) | Preprint (frozen; PDF only, no editable source) | [10.5281/zenodo.21313987](https://doi.org/10.5281/zenodo.21313987) | [10.5281/zenodo.21313986](https://doi.org/10.5281/zenodo.21313986) | [corpus/01-gods-and-slaves/Lee-Odinson_2026_Gods-and-Slaves_v1.2_preprint.pdf](corpus/01-gods-and-slaves/Lee-Odinson_2026_Gods-and-Slaves_v1.2_preprint.pdf) | CC BY 4.0 |
| II. *Peership: A Framework for Equitable Human–Machine Relations* | The normative and political argument for a relation of non-domination, standing, contestation, and co-authorship | v1.0 (2026-07-12) | Preprint (frozen; PDF only, no editable source) | [10.5281/zenodo.21315519](https://doi.org/10.5281/zenodo.21315519) | [10.5281/zenodo.21315518](https://doi.org/10.5281/zenodo.21315518) | [corpus/02-peership/Lee-Odinson_2026_Peership_v1.0_preprint.pdf](corpus/02-peership/Lee-Odinson_2026_Peership_v1.0_preprint.pdf) | CC BY 4.0 |
| III. *THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets* | One institutional implementation hypothesis — not proof of Peership, and not the only permitted implementation | v1.1 (2026-07-13) | Preprint (frozen; PDF only, no editable source) | [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) | [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) | [corpus/03-isonomia-commons/Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf](corpus/03-isonomia-commons/Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf) | CC BY 4.0 |
| IV. *Constitution, Not Cage* | An account of when constraint can be legitimate rather than dominating, and of the constitutional limits any implementation must satisfy | v1.0 (2026-07-12) | Preprint (frozen; PDF only, no editable source) | [10.5281/zenodo.21325361](https://doi.org/10.5281/zenodo.21325361) | [10.5281/zenodo.21325360](https://doi.org/10.5281/zenodo.21325360) | [corpus/04-constitution-not-cage/Lee-Odinson_2026_Constitution-Not-Cage_v1.0_preprint.pdf](corpus/04-constitution-not-cage/Lee-Odinson_2026_Constitution-Not-Cage_v1.0_preprint.pdf) | CC BY 4.0 |
| V. *The Peership Thesis: A Constitutional Research Program for Human–Machine Relations* | Canonical consolidation of the candidate research program — its boundaries, research questions, failure conditions, and relation to adjacent fields | v1.0 (2026-07-14) | Preprint (Markdown source and arXiv package committed) | [10.5281/zenodo.21359124](https://doi.org/10.5281/zenodo.21359124) | [10.5281/zenodo.21359123](https://doi.org/10.5281/zenodo.21359123) | [corpus/05-peership-thesis/Lee-Odinson_2026_Peership-Thesis_v1.0.pdf](corpus/05-peership-thesis/Lee-Odinson_2026_Peership-Thesis_v1.0.pdf) · [source/](corpus/05-peership-thesis/source/Lee-Odinson_2026_Peership-Thesis_v1.0.md) · [arxiv/](corpus/05-peership-thesis/arxiv/main.tex) | CC BY 4.0 |
| *The Peership Theses* (one-page companion) | **Companion, not a sixth paper.** Derivative one-page condensation of V | v1.0 (2026-07-14) | Preprint companion | **No DOI of its own** — deposited inside Zenodo record 21359124; cite [10.5281/zenodo.21359124](https://doi.org/10.5281/zenodo.21359124) | *(none of its own; see record 21359124)* | [corpus/companions/peership-theses/Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf](corpus/companions/peership-theses/Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf) · [source/](corpus/companions/peership-theses/source/Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.md) | CC BY 4.0 |
| `peership_sources.bib` (apparatus) | Canonical machine-readable source of truth; 161 BibTeX entries | Revision 1.3 (2026-07-14) | Live apparatus, synchronized | *No DOI of its own* — archived within record 21359124 (release zip) | *(none of its own)* | [apparatus/peership_sources.bib](apparatus/peership_sources.bib) | CC BY 4.0 |
| `peership_sourcebook.md` (apparatus) | Annotated bibliography and research map | v1.2 header, revision 1.3 (deposit day) — see [Apparatus versions](#apparatus-versions) | Live apparatus, synchronized | *No DOI of its own* — archived within record 21359124 (release zip) | *(none of its own)* | [apparatus/peership_sourcebook.md](apparatus/peership_sourcebook.md) | CC BY 4.0 |
| `peership_claim_ledger.md` (apparatus) | Claim-level provenance; ~71 logged claims (CL-F#, CL-D#, CL-G#, CL-P#, CL-I#, CL-C#, CL-T#) | v1.2 header, revision 1.3 (deposit day) — see [Apparatus versions](#apparatus-versions) | Live apparatus, synchronized | *No DOI of its own* — archived within record 21359124 (release zip) | *(none of its own)* | [apparatus/peership_claim_ledger.md](apparatus/peership_claim_ledger.md) | CC BY 4.0 |

### Licence split

All scholarly material in this repository — the papers, the PDFs, the Markdown, the apparatus, the bibliography, and the documentation — is **CC BY 4.0** ([LICENSE-DOCS](LICENSE-DOCS)). The Apache-2.0 licence in [LICENSE](LICENSE) is reserved for executable code and build scripts; **this repository currently contains no executable code.** The papers are not Apache-licensed. The file-level table above controls.

---

## ISONOMIA evidence table

ISONOMIA's implementation code and simulation data live in a **separate repository** and are deliberately not duplicated here: <https://github.com/dan-lee-odinson/isonomia-path-a>.

The firewall, stated verbatim:

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

| Item | Value |
|---|---|
| Preprint version | *THE ISONOMIA COMMONS*, v1.1 (2026-07-13) |
| Preprint exact-version DOI | [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) |
| Preprint concept DOI | [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) |
| Software concept DOI | [10.5281/zenodo.21287288](https://doi.org/10.5281/zenodo.21287288) |
| **Evidence-bearing software release** | **v1.0.0 (2026-07-10)** — the only release that supports the empirical claims |
| Evidence-bearing exact-version DOI | [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) |
| Git tag | `v1.0.0` |
| Commit hash | `ba3ddb5` (full: `ba3ddb51dbcc147def470b7af1eaddef6f349157`) |
| Document containing the empirical results | The ISONOMIA preprint ([10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917)), together with `CALIBRATION.md` in the implementation repository — a 45,000-run parameter sweep |
| Documentation release | v1.1.0 (2026-07-14) — DOI [10.5281/zenodo.21348073](https://doi.org/10.5281/zenodo.21348073), commit `def8f29` |
| What the documentation release changed | Documentation and claim language **only**. No code, simulation, data, or results changed. **The empirical evidence remains pinned to v1.0.0 / `ba3ddb5`**; cite that release, not v1.1.0, for any empirical claim. |

### Limitation on what the simulations establish

The simulations establish **sampled launch-economy behaviour only**. They do **not** establish constitutional legitimacy, they do **not** validate Peership, and nothing in ISONOMIA is live or production-validated. A parameter sweep can show that a designed mechanism behaves in a certain way under sampled conditions; it cannot show that the resulting institution would be legitimate, and legitimacy is the question Peership asks. Any citation of the sweep that omits this limitation misdescribes the evidence.

Supporting documents in the implementation repository (linked, not copied): `docs/ISONOMIA_Whitepaper_v0.6.3.md`, `docs/ISONOMIA_Tier1_Launch_Spec_v0.3.4.md`, `docs/ISONOMIA_PathA_Simulation_Plan_v0.1.2.md`, `docs/ISONOMIA_Feasibility_Assessment.md`, `CALIBRATION.md`, `VERSION_MANIFEST.md`.

---

## Recorded discrepancies

The rule this section exists to satisfy: **preserve the archived artifact, record the disagreement, do not silently modernise a frozen paper.** A discrepancy recorded here is not a defect to be patched out of the corpus; it is provenance. Nothing listed below was "fixed" in a frozen PDF.

### D1 — How the eleven deposited files are packaged in record 21359124

This is a packaging note, not a content discrepancy. The record is complete: all eleven files are present.

The Zenodo file list shows three entries — `Lee-Odinson_2026_Peership-Thesis_v1.0.pdf`, `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf`, and `Peership_v1.0_complete_release.zip`. The author's deposit sheet had listed eleven files. Both are right: the two PDFs were uploaded individually, and the remaining nine were bundled into the release zip, whose contents are:

| File in `Peership_v1.0_complete_release.zip` | Bytes |
|---|---:|
| `Lee-Odinson_2026_Peership-Thesis_v1.0.md` | 80,941 |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.md` | 4,502 |
| `peership_sourcebook.md` | 52,420 |
| `peership_claim_ledger.md` | 73,760 |
| `peership_sources.bib` | 94,253 |
| `Peership-Thesis_v1.0_latex_source.zip` | 32,247 |
| `POST_GATE_CHANGES.md` | 5,656 |
| `README.md` | 3,181 |
| `MANIFEST_sha256.txt` | 1,121 |

Two PDFs uploaded loose, plus nine inside the zip, is the eleven the deposit sheet describes.

**Controls:** the archived Zenodo record. **Changed:** nothing. Every one of those nine bundled files that this repository also ships was checked byte-for-byte against the copy inside the zip and is identical — see [`CHECKSUMS.sha256`](CHECKSUMS.sha256).

### D2 — ISONOMIA filename differs between Zenodo and this repository

On Zenodo the file is named `Lee-Odinson_2026_Isonomia-Commons_v1_1_preprint_UPDATE.pdf`. The repository copy is named `Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf` under the filename-hygiene rule.
**Controls:** the Zenodo record for the archival deposit; this repository's naming convention for the working copy. **Changed:** the filename only. **Not changed:** the byte content, which is untouched. The two files are the same document.

### D3 — The companion keeps its archived filename

The one-page companion retains `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf` rather than the shorter name sketched in the build spec, so that the repository filename matches Zenodo exactly.
**Controls:** the Zenodo record. **Changed:** nothing; the build spec's shorter name was not adopted.

### D4 — Numbering: *Constitution, Not Cage* and its "third in a series"

This is the discrepancy most likely to be misread, so it is stated precisely.

- The **front matter of *Constitution, Not Cage*** describes it as **"third in a series."** That is internally correct on its own terms: it counts **the essays only**, and the ISONOMIA design had preceded it as a *specification* rather than as an essay in the sequence.
- The **corpus's canonical reading order** is nonetheless **I. *Gods and Slaves* · II. *Peership* · III. *The Isonomia Commons* · IV. *Constitution, Not Cage* · V. *The Peership Thesis***. On that ordering **Isonomia is III and Constitution is IV**.
- The two are not in conflict about any fact. They are counting different things: the paper counts essays; the corpus orders the argument (genealogy → framework → implementation hypothesis → constraint theory → consolidation).
- The **revision-1.3 apparatus and *The Peership Thesis* already use the canonical order.** Only the older frozen PDFs use the essays-only numbering.

**Controls:** for the corpus, the canonical order above; for the text of the frozen paper, the frozen paper. **Changed:** nothing in the PDFs. *Constitution, Not Cage* still says "third in a series" and will continue to say so. **Do not** cite that phrase as evidence that the canonical reading order is III = Constitution.

### D5 — The other repository's manifest mislabels 10.5281/zenodo.21338480

The `isonomia-path-a` repository's own `VERSION_MANIFEST.md` still labels **10.5281/zenodo.21338480** the preprint **"concept DOI."** It is not. Per the Zenodo API and ledger entry **CL-D3**:

- **10.5281/zenodo.21338479** is the **concept (all-versions) DOI**.
- **10.5281/zenodo.21338480** is the **v1.0 exact-version DOI**.

This is an ordinary version-vs-inclusive pair, not a dispute about which work is which. The ISONOMIA paper's own front matter carries the same mislabelling; CL-D3 resolved it.
**Controls:** the Zenodo API, as recorded in CL-D3 and in this manifest. **Changed:** nothing outside this repository. Correcting the `isonomia-path-a` manifest is **out of scope** for this corpus build and remains open there.

### D6 — No editable sources exist for papers I–IV

Papers I–IV exist only as frozen PDFs; no editable source files were ever kept.
**Controls:** the facts of the archive. **Changed:** nothing. **Not created:** empty `source/` directories, which would have implied a source that does not exist. Only paper V and the one-page companion have committed sources.

### D7 — No reproducible search-protocol archive exists

No reproducible protocol files were archived at the time the searches were run. The author closed this item **as-is** (ledger CL-T2 / CL-T7; sourcebook rev. 1.3): the dated, non-exhaustive scan summary stands as the permanent record.
**Controls:** the author's closure decision, recorded in the ledger. **Changed:** nothing retroactive. The files in [apparatus/search_protocols/](apparatus/search_protocols/) are **dated open infrastructure** — they record which sources and domains were actually scanned, on what dates, with what result, and they state plainly that the exact query strings were not archived and the scan was not exhaustive. They supply a forward-looking template so that future re-runs are reproducible. **They do not reconstruct queries that were never archived, and they are not a claim of an exhaustive search.**

### Uptake baseline (dated negative — do not universalise)

"**No independent uptake identified**" — verified 2026-07-13, re-confirmed with no change 2026-07-14. Scanned: web, PhilPapers, Zenodo, and the GitHub repository. The scan was expressly **non-exhaustive**. At verification time the Zenodo records carried `noindex`; the `isonomia-path-a` repository had 0 stars and 0 forks, and its sole issue was self-authored.

The self-published **footprint** (footprint, not uptake) comprises five Zenodo deposits, the `isonomia-path-a` repository, a PhilArchive presence, and a Substack variant of *Gods and Slaves*. Unverified leads to convergent work exist (for example, republican-liberty-applied-to-AI work that does **not** cite this corpus). Convergence, if confirmed, would be **parallel invention, not uptake**, and such work is not cited here as a source. Peership is a **candidate** constitutional research program, not an established school with independent uptake.

---

## Apparatus versions

The three apparatus files must stay synchronized, and their version markers are not uniform. Describe them accurately rather than flattening them to "v1.3":

| File | What the file actually says | How to cite it |
|---|---|---|
| [apparatus/peership_sources.bib](apparatus/peership_sources.bib) | Header: **"Revision 1.3: 2026-07-14"**. Contains **161 BibTeX entries**. | `peership_sources.bib`, rev. 1.3 |
| [apparatus/peership_sourcebook.md](apparatus/peership_sourcebook.md) | Header line: **"Version: 1.2 · Date: 14 July 2026"**, **plus** a **"Revision 1.3 (deposit day, 2026-07-14)"** note recording the deposit-day closures. | "sourcebook, v1.2 header, revision 1.3 (deposit day)" |
| [apparatus/peership_claim_ledger.md](apparatus/peership_claim_ledger.md) | The same situation: a **"Version: 1.2"** header line **plus** a **"Revision 1.3 (deposit day, 2026-07-14)"** note. ~71 logged claims. | "claim ledger, v1.2 header, revision 1.3 (deposit day)" |

The `.bib` is the canonical machine-readable source of truth; where the three disagree on a bibliographic fact, the `.bib` controls. The sourcebook and ledger were **not** retitled to "v1.3" to tidy the record. Their headers say 1.2 and their revision notes say 1.3, and both statements are true of the file as deposited: the version header was not bumped on deposit day, while the deposit-day revision note was added. Rewriting the headers now would make the repository copies disagree with the copies archived in record 21359124, which is precisely the substitution this manifest exists to prevent.

---

## Review chain

The corpus passed a **four-round adversarial review** on 14 July 2026, using models from different laboratories. **Nothing in that process is evidence of machine political agency.** The review documents are provided for auditability and are **non-authoritative**: the frozen papers and the synchronized apparatus control.

- [reviews/canonical_adversarial_review.md](reviews/canonical_adversarial_review.md) — the full hostile review (r1.1)
- [reviews/draft2_adversarial_rereview.md](reviews/draft2_adversarial_rereview.md) — conditional pass
- [reviews/draft3_gate_confirmation_review.md](reviews/draft3_gate_confirmation_review.md) — gate confirmation, five narrower corrections
- [reviews/draft3_final_gate_receipt.md](reviews/draft3_final_gate_receipt.md) — receipt, with the five corrections restated
- [reviews/draft4_final_release_review.md](reviews/draft4_final_release_review.md) — the PASS
- [reviews/gate_dispositions.md](reviews/gate_dispositions.md)
- [reviews/post_gate_changes.md](reviews/post_gate_changes.md) — dated post-gate revision provenance

---

## The canonical thesis

Reproduce this compact form exactly wherever the thesis is stated. The three antecedent conditions and the **defeasible** character of the conclusion must survive every paraphrase.

> When an artificial entity has interests capable of being wronged, can understand and answer to public norms, and is enduringly governed by a shared basic structure without feasible exit, it acquires a defeasible claim to contestatory membership in that structure. Full Peership adds a consequential share in shaping and revising the basic rules.

It is not "anything governed deserves rights," and it must never be shortened to that.

The corpus does not claim that present AI systems are conscious, persons, or peers. It asks what institutions would be required **if** credible candidates for moral and political standing emerge.
