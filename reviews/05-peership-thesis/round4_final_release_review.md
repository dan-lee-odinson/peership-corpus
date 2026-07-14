# Peership Draft 4 — Final Release Review

**Review date:** 14 July 2026  
**Package reviewed:** `Peership_draft4_release_candidate.zip`  
**Package SHA-256:** `c73dec70cf7f7c3862d169e1c974b3cba5b9b4e81db2008f2aa53d3b6d28ef23`

## Final verdict

**PASS — the editorial and argument gate is cleared.** Draft 4 resolves all five remaining gate items, introduces no detected substantive regression, and is suitable to freeze as the canonical text for release production. No further adversarial review is warranted before formatting and deposit.

**One packaging qualification:** the ZIP is a complete *review* package, but it is not yet a complete *arXiv upload* package. It contains the canonical paper as Markdown and a render-check PDF only for the one-page Theses. It does not contain a TeX source bundle or a final PDF of the canonical paper. This is a production issue, not a defect in the paper's argument.

## Receipt and integrity

All manifest checks passed exactly.

| File | SHA-256 |
|---|---|
| `Lee-Odinson_2026_Peership-Thesis_v1.0_draft4.md` | `681dc86560e0e12de24d551610b2f225d993fa00ae683731108ecb79a303c355` |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0_draft4.md` | `b29b3f556c0cf2198fafb3b33358787f5c90b0603748d05d4d3927f91e17ef69` |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0_draft4_render-check.pdf` | `a9d1cd8bbdfa5cd7f3f07f1d06e3a47a5e5179e4fb25f20fc4b933a925e9eadd` |
| `POST_GATE_CHANGES.md` | `f529e4f0be5f08d851421d088f0661218edf12f1da19d3a0863d03d75c78bb6c` |
| `Peership-Thesis_draft3_GATE_DISPOSITIONS.md` | `b26c9b59f5609a239a49e1bed16bce62d0dbd7096673a20c3845bedbdfb808dc` |
| `Peership_apparatus_additions_PENDING.md` | `daa09d7306fec83c327f520ea4911ddc5c826121a4eb571d68f62d3953c22f09` |

The canonical paper arrived intact: **81,072 bytes, 394 lines, approximately 11,611 words**. Its final line is the complete Walzer 1977 entry ending with **“flagged in the corpus.]”** The earlier transfer-truncation concern therefore does not apply.

## Closure of the five gate items

| Gate item | Draft 4 disposition | Result |
|---|---|---|
| Aggregation standard | Section 9 now requires a consequential rule-formation route satisfying both amendment access and accountable representation or direct participation at the deciding stage. | **Cleared** |
| Exit/fork architecture | Sections 9 and 12 distinguish constitutive functions from anti-entrenchment safeguards and permit functional substitutes where exit or fork is omitted. | **Cleared** |
| Arbel–Salib–Goldstein author order | Corrected consistently in the paper, references, apparatus, and disposition record. The order matches the current arXiv record. | **Cleared** |
| Apparatus cross-references | The two canonical pointers were corrected from section 4 to section 5; the sourcebook section 4.3 reference was appropriately retained. | **Cleared** |
| One-page DOI rendering | Extracted PDF text reads exactly `10.5281/zenodo.21313987`; the former mid-identifier break is absent. | **Cleared** |

The narrowed fork scan is also correctly stated and no longer implies that the whole literature was searched for that exact term.

## Regression and consistency review

The Draft 3 to Draft 4 changes are confined to the intended gate repairs, version labeling, and accompanying audit notes. I found no change that reopens a settled position in the Peership corpus. In particular, Draft 4 continues to preserve:

- the separation between moral status and political standing;
- welfare protection as a floor rather than Peership itself;
- the distinction between consultation and constitutional co-authorship;
- the rejection of capability or power *alone* as a basis of entitlement;
- legitimate safety constraints under non-domination;
- the ideal-type status of the five postures;
- role reversal as a comparative diagnostic rather than a proof;
- the firewall between the Peership thesis and ISONOMIA as an implementation hypothesis; and
- open research debts without representing them as already solved.

The corrected reference order is independently confirmed by the current record for [Arbel, Salib, and Goldstein, *How to Count AIs*](https://arxiv.org/abs/2603.10028).

## One-page render review

The supplied render-check PDF is a single, unencrypted US-Letter page. It is legible and visually balanced, with no clipping, overflow, or malformed glyphs. The ORCID wraps within the compact author block but remains intact and readable. The footer DOI is displayed on one line and survives text extraction exactly.

## Release-production qualification

The canonical paper itself still needs an arXiv-compatible release artifact. Markdown is not among arXiv's listed submission formats; arXiv currently prefers TeX/LaTeX, followed by PDF and HTML. It also states that a PDF generated from available TeX/LaTeX source is typically rejected in favor of the source. See arXiv's official [submission overview](https://info.arxiv.org/help/submit/index.html) and [PDF submission guidance](https://info.arxiv.org/help/submit_pdf.html).

Accordingly, freeze the canonical text at SHA-256 `681dc865…303c355`, then:

1. Produce and compile a clean TeX source bundle for the canonical paper, including the bibliography material needed for arXiv to compile it.
2. Inspect arXiv's generated preview page by page and confirm that the paper ends with the complete Walzer entry.
3. Apply the pending apparatus atomically and complete the release-day source, metadata-resolution, and search-protocol checks already recorded in `POST_GATE_CHANGES.md`.
4. For a Zenodo or repository release, include the final canonical-paper PDF as well as the source and one-page Theses.
5. Generate a new manifest over the exact deposit bundle.

DOI assignment is **not** a prerequisite to the initial arXiv submission. arXiv's metadata guidance reserves its DOI field for a resolving DOI of another published version and permits it to be added later; arXiv also assigns its own DOI after submission. See [arXiv metadata guidance](https://info.arxiv.org/help/prep.html#doi).

## Release decision

**Accept Draft 4. Freeze substantive editing. Move to typesetting, final apparatus application, and deposit packaging.** The only remaining blocker is production of the canonical-paper submission artifact and completion of the already acknowledged deposit-day operations; it is not another conceptual or adversarial-review blocker.
