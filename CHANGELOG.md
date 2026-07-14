# Changelog

All notable changes to **this repository** are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this repository's releases follow [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Scope of this file

This changelog tracks **releases of this repository** — what was assembled, when, and in what arrangement. It does **not** track the frozen papers.

The papers are archival deposits. Their history lives in **Zenodo** (each work has a concept DOI and per-version exact DOIs) and, for the substantive drafting record of *The Peership Thesis*, in [reviews/post_gate_changes.md](reviews/post_gate_changes.md). A release of this repository never changes a paper, never advances a paper's version number, and never mints a DOI: GitHub–Zenodo auto-archiving is deliberately not enabled, because the Zenodo records are already the archival scholarly deposits. See [VERSION_MANIFEST.md](VERSION_MANIFEST.md) for the three independent version layers and why they must not be substituted for one another.

---

## [1.0.0] — 2026-07-14

Initial synchronized corpus release. This assembles, for the first time in one place, the five frozen papers, the derivative one-page companion, the apparatus at revision 1.3, and the full adversarial review chain, with every version and identifier verified against the Zenodo REST API on the release date.

### Added

**The five corpus works**, in canonical reading order (argumentative, not chronological: genealogy → framework → implementation hypothesis → constraint theory → consolidation):

1. *Gods and Slaves* (v1.2) — [corpus/01-gods-and-slaves/](corpus/01-gods-and-slaves/)
2. *Peership: A Framework for Equitable Human–Machine Relations* (v1.0) — [corpus/02-peership/](corpus/02-peership/)
3. *THE ISONOMIA COMMONS* (v1.1) — [corpus/03-isonomia-commons/](corpus/03-isonomia-commons/)
4. *Constitution, Not Cage* (v1.0) — [corpus/04-constitution-not-cage/](corpus/04-constitution-not-cage/)
5. *The Peership Thesis* (v1.0) — [corpus/05-peership-thesis/](corpus/05-peership-thesis/), with Markdown source and arXiv package

- **The one-page companion**, *The Peership Theses* (v1.0), in [corpus/companions/peership-theses/](corpus/companions/peership-theses/) — a derivative condensation of work V, not a sixth paper. It has no DOI of its own and is cited by the DOI of Zenodo record 21359124, inside which it was deposited.
- **The apparatus**, at revision 1.3 (deposit day, 2026-07-14): [`peership_sources.bib`](apparatus/peership_sources.bib) (161 entries, header "Revision 1.3: 2026-07-14"), [`peership_sourcebook.md`](apparatus/peership_sourcebook.md), and [`peership_claim_ledger.md`](apparatus/peership_claim_ledger.md) (~71 logged claims). The sourcebook and ledger carry a **"Version: 1.2" header line plus a "Revision 1.3 (deposit day, 2026-07-14)" note**; that mixed marking is deliberate and is described exactly in [VERSION_MANIFEST.md](VERSION_MANIFEST.md#apparatus-versions) rather than flattened.
- **Dated search-protocol infrastructure** in [apparatus/search_protocols/](apparatus/search_protocols/): a record of the sources and domains actually scanned, the dates, and the results, with the explicit limitation that the exact query strings were never archived and the scan was not exhaustive, plus a forward-looking template so that future re-runs are reproducible.
- **The full review chain** in [reviews/](reviews/) — the canonical hostile review, the draft-2 conditional pass, the draft-3 gate confirmation and receipt, the draft-4 PASS, the gate dispositions, and the post-gate change log. The corpus passed a four-round adversarial review on 14 July 2026, using models from different laboratories. Nothing in that process is evidence of machine political agency. These documents are non-authoritative: the frozen papers and the synchronized apparatus control.
- **[VERSION_MANIFEST.md](VERSION_MANIFEST.md)** — the authoritative version record: the three version layers, the one authoritative version table, the ISONOMIA evidence table (with its limitation), the recorded discrepancies, and the apparatus-version note.
- **Licence files** — [LICENSE-DOCS](LICENSE-DOCS) (CC BY 4.0) and [LICENSE](LICENSE) (Apache-2.0).

### Established

- **Canonical reading order: I. *Gods and Slaves* · II. *Peership* · III. *The Isonomia Commons* · IV. *Constitution, Not Cage* · V. *The Peership Thesis*.** The revision-1.3 apparatus and *The Peership Thesis* already use this order. The older frozen PDFs do not, and were not altered — see discrepancy D4.
- **Licence split.** All scholarly material — papers, PDFs, Markdown, apparatus, bibliography, documentation — is **CC BY 4.0**. Apache-2.0 is reserved for executable code and build scripts; **the repository currently contains no executable code.** The papers are not Apache-licensed; the file-level table in the manifest controls.
- **Separation of the implementation.** ISONOMIA's code and simulation data are not duplicated here. They remain in <https://github.com/dan-lee-odinson/isonomia-path-a>, and the empirical evidence is pinned to software release **v1.0.0 / commit `ba3ddb5`** (DOI 10.5281/zenodo.21287289). The v1.1.0 release (DOI 10.5281/zenodo.21348073, commit `def8f29`) changed documentation and claim language only.

### Recorded (not fixed)

Seven discrepancies (D1–D7) are documented in [VERSION_MANIFEST.md](VERSION_MANIFEST.md#recorded-discrepancies) rather than silently repaired: the file count in Zenodo record 21359124; the ISONOMIA filename difference between Zenodo and this repository; the companion's archived filename; the *Constitution, Not Cage* "third in a series" numbering; the `…21338480` concept-vs-version DOI mislabelling in the separate `isonomia-path-a` manifest; the absence of editable sources for papers I–IV; and the absence of a reproducible search-protocol archive. **The archived artifacts control. No frozen paper was modernised.**

### Upstream revision history (context, not repository changes)

The substantive drafting history below concerns *The Peership Thesis* and its package, not this repository. It is summarized from [reviews/post_gate_changes.md](reviews/post_gate_changes.md), which is the authoritative record.

- **Draft 4 (14 July 2026)** — applied the five corrections from the draft-3 final-gate receipt; no other substantive text changed between drafts 3 and 4. (1) §9 aggregation conformed to §§2–3, so that both rival-design invitations (§9, §12) require the constitutive functions plus credible anti-entrenchment safeguards, with functional substitutes where exit or fork is omitted. (2) The author order of *How to Count AIs* corrected to Arbel, Salib, Goldstein per the arXiv record, in the prose, the reference entry, the pending BibTeX, and the draft-3 dispositions note. (3) Pending-apparatus section pointers fixed to cite canonical §5. (4) The fork-scan claim narrowed to the materials actually reviewed: no implemented analogue of executable, unconfiscated fork was identified among the constitutional secession clauses and emigration-rights instruments in the apparatus, and the claim is limited to those materials. (5) The one-pager re-rendered with hyphenation disabled, so the footer DOI displays and extracts intact, still on one US-Letter page at 10-pt type.
- **Draft 5 (14 July 2026)** — the author's corpus-order correction. Metadata only; no argumentative text changed. The corpus order was set to I–V as above; the front-matter sequence line, lineage block, opening work list, §12 table row order, and one-pager footer DOI order were updated, with a note explaining that *Constitution, Not Cage*'s own "third in a sequence" self-description counts essays only. Reference letters (2026c = *Constitution*, 2026d = *Isonomia*) are citation-order labels, not corpus-order labels, and were left unchanged. A cross-corpus consistency item — the sourcebook and ledger still ordering *Constitution* before *Isonomia* — was logged for reconciliation at apparatus application.
- **Draft 6 (14 July 2026)** — reference-section cleanup after the apparatus was applied (`.bib` rev. 1.1; sourcebook v1.1; ledger v1.1). In-process notations were removed: "add to `.bib`" flags replaced with resolved citation keys (`arbel2026counting`, `cooperativeai_foundation`, `pluralistic2026icml`); "verify before deposit" clauses removed from four entries, those checks remaining tracked in the ledger (CL-T2/CL-T7) rather than in the paper; the `…21338480` clause pointed at ledger CL-D3. No argumentative text changed. The one-pager was unchanged and remained at Draft 5. "DOI pending" remained in the front matter as a true status.
- **v1.0 release finalization (14 July 2026)** — the reserved Zenodo DOI **10.5281/zenodo.21359124** was recorded across the package (paper front matter and how-to-cite block, one-pager header and footer, `.bib` rev. 1.2, sourcebook v1.2, ledger v1.2), the forthcoming-theses placeholder key was replaced by `leeodinson2026thesis` and `leeodinson2026theses_onepager`, and the front matter changed from "Draft" to "Preprint · Version 1.0". One Zenodo record covers the full package.
- **Deposit day (14 July 2026)** — the pre-publish checklist was closed. The uptake scan was re-run with no change from 2026-07-13 (logged in CL-T2). Search-protocol archiving was closed **as-is**, the dated, non-exhaustive scan summary standing as the permanent record (CL-T2/CL-T7). The `…21338480` question was resolved: it is the v1.0 exact-version DOI, and 10.5281/zenodo.21338479 is the concept (all-versions) DOI — an ordinary version-vs-inclusive pair, not a dispute (CL-D3). Citation spot-checks were author-confirmed and the file manifest regenerated. The apparatus reached revision 1.3.

### Standing caveats

- **Uptake:** "No independent uptake identified" — verified 2026-07-13, re-confirmed with no change 2026-07-14, across web, PhilPapers, Zenodo, and the GitHub repository. The scan was expressly non-exhaustive. This is a dated negative and must not be universalised. Peership is a **candidate** constitutional research program, not an established school with independent uptake.
- **ISONOMIA:** one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership. Its 45,000-run parameter sweep establishes sampled launch-economy behaviour only; it does not establish constitutional legitimacy, does not validate Peership, and nothing is live or production-validated.
- **Claim discipline:** the corpus does not claim that present AI systems are conscious, persons, or peers. It asks what institutions would be required **if** credible candidates for moral and political standing emerge.

[1.0.0]: https://github.com/dan-lee-odinson/peership-corpus/releases/tag/v1.0.0
