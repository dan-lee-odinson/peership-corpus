# Citations

Ready-to-copy citations for every item in the Peership corpus, in plain text and BibTeX.

All metadata below was verified against the Zenodo REST API on 14 July 2026.

---

## Which DOI do I use?

Every Zenodo record carries **two kinds of DOI**, and they do different jobs.

| | **Concept DOI** (all versions) | **Exact-version DOI** |
|---|---|---|
| What it identifies | The work as such, across all its versions | One immutable deposit: one text, one file set, one date |
| Where it resolves | Always to the *latest* version | Always to the *same* version, forever |
| Changes when a new version is deposited | No — it keeps pointing at the newest | No — it keeps pointing at the version it names |
| What a reader gets | Whatever the current version happens to be | Exactly the text you read |

**The rule: a scholarly reference to a fixed text must use the EXACT-VERSION DOI.**

If you quote a passage, cite a page, attribute a claim, or rely on a result, your reader must be able to retrieve *the text you actually read*. A concept DOI cannot guarantee that: the moment a new version is deposited, the concept DOI resolves somewhere else, and your quotation may no longer be there. Cite the exact-version DOI, and give the version number alongside it.

Use the **concept DOI** only when you deliberately mean *the work in general, whatever its current version* — for example, in a reading list, a "see also", or a link inviting readers to the newest text. Never in support of a specific claim.

The same rule governs software with even less slack. Empirical claims that rest on a simulation must cite the **exact-version software DOI** and the commit, not the concept DOI. See item 10.

### Quick reference

| # | Work | Version | Exact-version DOI | Concept DOI |
|---|---|---|---|---|
| 1 | Gods and Slaves | v1.2 | `10.5281/zenodo.21313987` | `10.5281/zenodo.21313986` |
| 2 | Peership | v1.0 | `10.5281/zenodo.21315519` | `10.5281/zenodo.21315518` |
| 3 | The Isonomia Commons | v1.1 | `10.5281/zenodo.21343917` | `10.5281/zenodo.21338479` |
| 4 | Constitution, Not Cage | v1.0 | `10.5281/zenodo.21325361` | `10.5281/zenodo.21325360` |
| 5 | The Peership Thesis | v1.0 | `10.5281/zenodo.21359124` | `10.5281/zenodo.21359123` |
| 6 | The Peership Theses (one-pager) | v1.0 | *(no DOI of its own — cited by record 21359124)* | — |
| 7 | The Peership Sourcebook | rev. 1.3 | *(no DOI of its own — deposited within record 21359124)* | — |
| 8 | The Peership Claim Ledger | rev. 1.3 | *(no DOI of its own — deposited within record 21359124)* | — |
| 9 | Complete Zenodo package | v1.0 | `10.5281/zenodo.21359124` | `10.5281/zenodo.21359123` |
| 10 | ISONOMIA software | v1.0.0 | `10.5281/zenodo.21287289` | `10.5281/zenodo.21287288` |

### A note on this repository

**This GitHub repository has no DOI.** Its release tags (`v1.0.0`, ...) are a third, independent version layer: they are not paper versions and they do not mint DOIs. GitHub–Zenodo auto-archiving is deliberately not enabled, because the Zenodo records above are already the archival scholarly deposits. To cite the ideas, cite the work. To cite the collection as a container, use [`CITATION.cff`](CITATION.cff) and name the release version.

---

## 1. Gods and Slaves

Genealogy and literary-philosophical diagnosis of inherited human postures toward nonhuman intelligence.

- **Exact-version DOI (cite this): `10.5281/zenodo.21313987`** — v1.2, 11 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21313986`
- Preprint. CC BY 4.0. Repository copy: [`corpus/01-gods-and-slaves/`](corpus/01-gods-and-slaves/)

**Plain text**

> Lee-Odinson, D. (2026). *Gods and Slaves: AI and the Debate of Humanity's Relationship with the Other* (Version v1.2) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21313987

**BibTeX**

```bibtex
@misc{leeodinson2026godsandslaves,
  author       = {Lee-Odinson, Dan},
  title        = {Gods and Slaves: {AI} and the Debate of Humanity's Relationship with the Other},
  year         = {2026},
  month        = {7},
  version      = {v1.2},
  howpublished = {Preprint},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21313987},
  url          = {https://doi.org/10.5281/zenodo.21313987},
  note         = {Exact-version DOI for v1.2. Concept (all-versions) DOI: 10.5281/zenodo.21313986},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 2. Peership

The normative and political argument for a relation of non-domination, standing, contestation, and co-authorship.

- **Exact-version DOI (cite this): `10.5281/zenodo.21315519`** — v1.0, 12 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21315518`
- Preprint. CC BY 4.0. Repository copy: [`corpus/02-peership/`](corpus/02-peership/)

**Plain text**

> Lee-Odinson, D. (2026). *Peership: A Framework for Equitable Human–Machine Relations* (Version v1.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21315519

**BibTeX**

```bibtex
@misc{leeodinson2026peership,
  author       = {Lee-Odinson, Dan},
  title        = {Peership: A Framework for Equitable Human--Machine Relations},
  year         = {2026},
  month        = {7},
  version      = {v1.0},
  howpublished = {Preprint},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21315519},
  url          = {https://doi.org/10.5281/zenodo.21315519},
  note         = {Exact-version DOI for v1.0. Concept (all-versions) DOI: 10.5281/zenodo.21315518},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 3. The Isonomia Commons

One institutional implementation hypothesis. Not a proof of Peership, and not the only permitted implementation.

- **Exact-version DOI (cite this): `10.5281/zenodo.21343917`** — v1.1, 13 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21338479`
- Preprint. CC BY 4.0. Repository copy: [`corpus/03-isonomia-commons/`](corpus/03-isonomia-commons/)

The title is capitalised as `THE ISONOMIA COMMONS` on the archived record; it is reproduced that way below.

> **A third DOI you may encounter — and it is a valid one.** `10.5281/zenodo.21338480` is the **v1.0 exact-version DOI**. It is not stale or superseded: it permanently pins v1.0, and it is the right thing to cite if v1.0 is what you mean. What is wrong is only its *label* — the paper's own front matter calls it the "concept DOI," which it is not. The concept (all-versions) DOI is `10.5281/zenodo.21338479`. Ledger entry CL-D3 resolved this against the Zenodo API; the frozen PDF was not altered. So: cite `…21338479` for the work as a whole, `…21343917` for the deposited v1.1, and `…21338480` only when you specifically mean v1.0 — but never call `…21338480` a concept DOI.

**Plain text**

> Lee-Odinson, D. (2026). *THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets* (Version v1.1) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21343917

**BibTeX**

```bibtex
@misc{leeodinson2026isonomiacommons,
  author       = {Lee-Odinson, Dan},
  title        = {{THE ISONOMIA COMMONS}: A Constitutional Design for Autonomous Agent Labor Markets},
  year         = {2026},
  month        = {7},
  version      = {v1.1},
  howpublished = {Preprint},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21343917},
  url          = {https://doi.org/10.5281/zenodo.21343917},
  note         = {Exact-version DOI for v1.1. Concept (all-versions) DOI: 10.5281/zenodo.21338479.
                  10.5281/zenodo.21338480 is the v1.0 exact-version DOI, not a concept DOI},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

---

## 4. Constitution, Not Cage

An account of when constraint can be legitimate rather than dominating, and of the constitutional limits any implementation must satisfy.

- **Exact-version DOI (cite this): `10.5281/zenodo.21325361`** — v1.0, 12 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21325360`
- Preprint. CC BY 4.0. Repository copy: [`corpus/04-constitution-not-cage/`](corpus/04-constitution-not-cage/)

> **Numbering note.** The frozen PDF's front matter describes this paper as "third in a series": it counts the essays only, the ISONOMIA design having preceded it as a specification. The corpus's canonical reading order places Isonomia at III and Constitution at IV. The frozen PDF is preserved unchanged; the discrepancy is recorded, not repaired.

**Plain text**

> Lee-Odinson, D. (2026). *Constitution, Not Cage* (Version v1.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21325361

**BibTeX**

```bibtex
@misc{leeodinson2026constitutionnotcage,
  author       = {Lee-Odinson, Dan},
  title        = {Constitution, Not Cage},
  year         = {2026},
  month        = {7},
  version      = {v1.0},
  howpublished = {Preprint},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21325361},
  url          = {https://doi.org/10.5281/zenodo.21325361},
  note         = {Exact-version DOI for v1.0. Concept (all-versions) DOI: 10.5281/zenodo.21325360},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 5. The Peership Thesis

The canonical consolidation of the candidate research program: its boundaries, research questions, failure conditions, and relation to adjacent fields. **This is the work to cite when citing the program as such**, and it is the `preferred-citation` in [`CITATION.cff`](CITATION.cff).

- **Exact-version DOI (cite this): `10.5281/zenodo.21359124`** — v1.0, 14 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21359123`
- Preprint. CC BY 4.0. Repository copy: [`corpus/05-peership-thesis/`](corpus/05-peership-thesis/) (PDF, Markdown source, and arXiv package)

**Plain text**

> Lee-Odinson, D. (2026). *The Peership Thesis: A Constitutional Research Program for Human–Machine Relations* (Version v1.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21359124

**BibTeX**

```bibtex
@misc{leeodinson2026peershipthesis,
  author       = {Lee-Odinson, Dan},
  title        = {The Peership Thesis: A Constitutional Research Program for Human--Machine Relations},
  year         = {2026},
  month        = {7},
  version      = {v1.0},
  howpublished = {Preprint},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21359124},
  url          = {https://doi.org/10.5281/zenodo.21359124},
  note         = {Exact-version DOI for v1.0. Concept (all-versions) DOI: 10.5281/zenodo.21359123},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 6. The Peership Theses (one-page companion — not a sixth paper)

A one-page companion to the canonical thesis. It is **derivative, not a sixth paper**.

> **This companion has NO DOI of its own.** It was deposited *inside* Zenodo record 21359124 and is cited by **that same DOI**: `10.5281/zenodo.21359124`. There is no separate identifier to look for, and none should be invented. When you cite the companion you are citing record 21359124; name the companion in the title and identify the specific file so a reader can find it within the record.

- **DOI to use: `10.5281/zenodo.21359124`** (the exact-version DOI of the record it lives in — see item 5)
- File within the record: `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf`
- CC BY 4.0. Repository copy: [`corpus/companions/peership-theses/`](corpus/companions/peership-theses/)

**Plain text**

> Lee-Odinson, D. (2026). *The Peership Theses* (Version v1.0) [One-page companion to *The Peership Thesis*]. In *The Peership Thesis: A Constitutional Research Program for Human–Machine Relations*. Zenodo. https://doi.org/10.5281/zenodo.21359124 (File: `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf`)

**BibTeX**

```bibtex
@misc{leeodinson2026peershiptheses,
  author       = {Lee-Odinson, Dan},
  title        = {The Peership Theses (One-Page Companion)},
  year         = {2026},
  month        = {7},
  version      = {v1.0},
  howpublished = {Deposited within Zenodo record 21359124},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21359124},
  url          = {https://doi.org/10.5281/zenodo.21359124},
  note         = {This companion has no DOI of its own; it is cited by the DOI of record 21359124,
                  the exact-version DOI of The Peership Thesis v1.0.
                  File: Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 7. The Peership Sourcebook (apparatus)

Annotated bibliography and research map.

> **No independent DOI.** The sourcebook was deposited *within* Zenodo record 21359124 (inside `Peership_v1.0_complete_release.zip`). Cite **the record's DOI**, and additionally cite **the file and its revision**, because the apparatus is revised on a cycle of its own and a bare record DOI will not tell your reader which revision you read.

- **DOI to use: `10.5281/zenodo.21359124`** (the record; see item 9)
- File: `peership_sourcebook.md` — **v1.2 header, revision 1.3 (deposit day, 14 July 2026)**
- CC BY 4.0. Repository copy: [`apparatus/peership_sourcebook.md`](apparatus/peership_sourcebook.md)

The header line reads `Version: 1.2 · Date: 14 July 2026` and carries a `Revision 1.3 (deposit day, 2026-07-14)` note. Cite it as "v1.2 header, revision 1.3"; do not silently promote it to v1.3.

**Plain text**

> Lee-Odinson, D. (2026). *The Peership Sourcebook* (v1.2 header, revision 1.3, 14 July 2026) [Annotated bibliography and research map]. In *The Peership Thesis* (Version v1.0). Zenodo. https://doi.org/10.5281/zenodo.21359124 (File: `peership_sourcebook.md`, in `Peership_v1.0_complete_release.zip`)

**BibTeX**

```bibtex
@misc{leeodinson2026sourcebook,
  author       = {Lee-Odinson, Dan},
  title        = {The Peership Sourcebook: Annotated Bibliography and Research Map},
  year         = {2026},
  month        = {7},
  version      = {v1.2 header, revision 1.3},
  howpublished = {Deposited within Zenodo record 21359124},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21359124},
  url          = {https://doi.org/10.5281/zenodo.21359124},
  note         = {No independent DOI; cited by the DOI of record 21359124.
                  File: peership_sourcebook.md, in Peership_v1.0_complete_release.zip.
                  Header reads Version 1.2; carries a Revision 1.3 (deposit day, 2026-07-14) note.
                  Companion machine-readable bibliography: peership_sources.bib, Revision 1.3
                  (2026-07-14), 161 entries},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 8. The Peership Claim Ledger (apparatus)

Claim-level provenance: 70 logged claims, with identifiers of the form `CL-F#`, `CL-D#`, `CL-G#`, `CL-P#`, `CL-I#`, `CL-C#`, `CL-T#`.

(The ledger itself, the sourcebook, and *The Peership Thesis* all describe the coverage as "~71 logged claims." The file contains 70 unique claim IDs. The discrepancy is recorded as erratum **E2** in [`apparatus/corrections_log.md`](apparatus/corrections_log.md) and will be reconciled at the next apparatus revision. The frozen artifacts are not altered to fix it.)

> **No independent DOI**, exactly as with the sourcebook. It was deposited *within* Zenodo record 21359124 (inside `Peership_v1.0_complete_release.zip`). Cite **the record's DOI**, plus **the file and its revision**. When you rely on a specific claim, cite its claim ID as well — that is what the ledger is for.

- **DOI to use: `10.5281/zenodo.21359124`** (the record; see item 9)
- File: `peership_claim_ledger.md` — **v1.2 header, revision 1.3 (deposit day, 14 July 2026)**
- CC BY 4.0. Repository copy: [`apparatus/peership_claim_ledger.md`](apparatus/peership_claim_ledger.md)

**Plain text**

> Lee-Odinson, D. (2026). *The Peership Claim Ledger* (v1.2 header, revision 1.3, 14 July 2026) [Claim-level provenance record]. In *The Peership Thesis* (Version v1.0). Zenodo. https://doi.org/10.5281/zenodo.21359124 (File: `peership_claim_ledger.md`, in `Peership_v1.0_complete_release.zip`)

**BibTeX**

```bibtex
@misc{leeodinson2026claimledger,
  author       = {Lee-Odinson, Dan},
  title        = {The Peership Claim Ledger: Claim-Level Provenance},
  year         = {2026},
  month        = {7},
  version      = {v1.2 header, revision 1.3},
  howpublished = {Deposited within Zenodo record 21359124},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21359124},
  url          = {https://doi.org/10.5281/zenodo.21359124},
  note         = {No independent DOI; cited by the DOI of record 21359124.
                  File: peership_claim_ledger.md, in Peership_v1.0_complete_release.zip.
                  Header reads Version 1.2; carries a Revision 1.3 (deposit day, 2026-07-14) note.
                  When citing a specific claim, give its claim ID (e.g. CL-D3)},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 9. The complete Zenodo package (record 21359124)

Cite this when you mean **the deposit as a whole** — thesis, companion, and apparatus together — rather than one document inside it.

- **Exact-version DOI (cite this): `10.5281/zenodo.21359124`** — v1.0, 14 July 2026
- Concept DOI (all versions, resolves to latest): `10.5281/zenodo.21359123`
- Record: https://zenodo.org/records/21359124
- CC BY 4.0

**As published, record 21359124 contains three files:**

| File | Content |
|---|---|
| `Lee-Odinson_2026_Peership-Thesis_v1.0.pdf` | The canonical thesis (item 5) |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf` | The one-page companion (item 6) |
| `Peership_v1.0_complete_release.zip` | The complete release bundle, including the apparatus (items 7 and 8) |

The apparatus files are therefore **inside the zip**, not uploaded separately. An earlier local deposit metadata sheet had described eleven separately-uploaded files; the archived record is what exists and what controls. Nothing was changed to make the record match the sheet.

**Plain text**

> Lee-Odinson, D. (2026). *The Peership Thesis: A Constitutional Research Program for Human–Machine Relations* — complete release package (Version v1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.21359124

**BibTeX**

```bibtex
@misc{leeodinson2026peershippackage,
  author       = {Lee-Odinson, Dan},
  title        = {The Peership Thesis: A Constitutional Research Program for Human--Machine Relations
                  --- Complete Release Package},
  year         = {2026},
  month        = {7},
  version      = {v1.0},
  howpublished = {Zenodo record 21359124},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21359124},
  url          = {https://doi.org/10.5281/zenodo.21359124},
  note         = {Exact-version DOI for v1.0. Concept (all-versions) DOI: 10.5281/zenodo.21359123.
                  The record as published contains three files: the thesis PDF, the one-page
                  companion PDF, and Peership_v1.0_complete_release.zip},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

---

## 10. The ISONOMIA software and simulation release

Source repository: https://github.com/dan-lee-odinson/isonomia-path-a (a separate repository; the code and data are not duplicated in this corpus). Overview: [`implementations/isonomia.md`](implementations/isonomia.md)

| | DOI | Tag | Commit | Date |
|---|---|---|---|---|
| **Concept DOI** (all versions) | `10.5281/zenodo.21287288` | — | — | — |
| **Exact release v1.0.0 — EVIDENCE-BEARING** | **`10.5281/zenodo.21287289`** | `v1.0.0` | `ba3ddb5` | 10 July 2026 |
| Documentation release v1.1.0 | `10.5281/zenodo.21348073` | — | `def8f29` | 14 July 2026 |

Full commit hash for v1.0.0: `ba3ddb51dbcc147def470b7af1eaddef6f349157`

> **Empirical claims must cite the exact-version software DOI `10.5281/zenodo.21287289`, not the concept DOI `10.5281/zenodo.21287288`.**
>
> This is not a stylistic preference. The concept DOI resolves to whatever version is current, so it names no particular code. A result is only reproducible against the code that produced it. Any claim about the 45,000-run parameter sweep, or about any simulated launch-economy behaviour, is evidence-bearing **only** with respect to release **v1.0.0 / `10.5281/zenodo.21287289` / commit `ba3ddb5`**. Cite the exact-version DOI and the commit together.
>
> Documentation release **v1.1.0** (`10.5281/zenodo.21348073`, commit `def8f29`) changed **documentation and claim language only**. No code, simulation, data, or results changed. It does not supersede v1.0.0 as the evidentiary basis, and it must not be cited as the source of an empirical result. The evidence remains pinned to v1.0.0 / `ba3ddb5`.

**What the simulations do and do not show.** They establish sampled launch-economy behaviour only. They do **not** establish constitutional legitimacy, do **not** validate Peership, and nothing in them is live or production-validated. The empirical results are reported in the ISONOMIA preprint (item 3, `10.5281/zenodo.21343917`) and in the repository's `CALIBRATION.md`.

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

**Plain text (exact version — use this for empirical claims)**

> Lee-Odinson, D. (2026). *ISONOMIA: Path A simulation and software release* (Version v1.0.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.21287289 (Git tag `v1.0.0`, commit `ba3ddb5`)

**Plain text (concept — for a general pointer only, never for a result)**

> Lee-Odinson, D. (2026). *ISONOMIA: Path A simulation and software* [Software]. Zenodo. https://doi.org/10.5281/zenodo.21287288

**BibTeX**

```bibtex
@software{leeodinson2026isonomiasoftware,
  author       = {Lee-Odinson, Dan},
  title        = {{ISONOMIA}: Path A Simulation and Software Release},
  year         = {2026},
  month        = {7},
  version      = {v1.0.0},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21287289},
  url          = {https://doi.org/10.5281/zenodo.21287289},
  repository   = {https://github.com/dan-lee-odinson/isonomia-path-a},
  note         = {EVIDENCE-BEARING exact-version DOI. Git tag v1.0.0, commit ba3ddb5
                  (ba3ddb51dbcc147def470b7af1eaddef6f349157), 2026-07-10.
                  Empirical claims must cite this exact-version DOI, NOT the concept
                  (all-versions) DOI 10.5281/zenodo.21287288.
                  Documentation release v1.1.0 (10.5281/zenodo.21348073, commit def8f29)
                  changed documentation and claim language only; no code, simulation, data,
                  or results changed},
  orcid        = {https://orcid.org/0009-0009-9504-0796}
}
```

With a plain (non-biblatex) BibTeX style that does not know `@software`, change the entry type to `@misc` and add `howpublished = {Software}`.

---

## Scope of what is being cited

The corpus does not claim that present AI systems are conscious, persons, or peers. It asks what institutions would be required **if** credible candidates for moral and political standing emerge. Peership is a candidate constitutional research program, not an established school with independent uptake.

The canonical thesis, in the compact form that should survive any paraphrase:

> When an artificial entity has interests capable of being wronged, can understand and answer to public norms, and is enduringly governed by a shared basic structure without feasible exit, it acquires a defeasible claim to contestatory membership in that structure. Full Peership adds a consequential share in shaping and revising the basic rules.

The three antecedent conditions and the defeasible character of the conclusion are load-bearing. Do not shorten the thesis to "anything governed deserves rights."
