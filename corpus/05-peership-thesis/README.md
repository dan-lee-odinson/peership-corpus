# The Peership Thesis: A Constitutional Research Program for Human–Machine Relations

**Author:** Dan Lee-Odinson
**Version:** v1.0
**Status:** Preprint
**Exact-version DOI:** [10.5281/zenodo.21359124](https://doi.org/10.5281/zenodo.21359124)
**Concept DOI:** [10.5281/zenodo.21359123](https://doi.org/10.5281/zenodo.21359123)
**License:** CC BY 4.0

## Role in the corpus

Paper V is the canonical consolidation of the candidate research program. It states the thesis in its authoritative compact form, fixes the program's boundaries, sets out its research questions and its failure conditions, and locates it relative to adjacent fields. Where the earlier papers disagree with it on numbering or nomenclature, this paper and the revision-1.3 apparatus control; the frozen PDFs of Papers I–IV are preserved unchanged.

The canonical statement, which must survive every paraphrase with its three antecedent conditions and its defeasible conclusion intact:

> When an artificial entity has interests capable of being wronged, can understand and answer to public norms, and is enduringly governed by a shared basic structure without feasible exit, it acquires a defeasible claim to contestatory membership in that structure. Full Peership adds a consequential share in shaping and revising the basic rules.

What it does **not** establish: consolidating a program is not vindicating it. The paper does not show that Peership is uniquely correct, technically feasible, or established; it does not claim that present AI systems are conscious, persons, or peers; and it does not treat model self-reports as evidence of consciousness or political agency. Peership remains a **candidate** constitutional research program: no independent uptake was identified in the sources scanned — web, PhilPapers, Zenodo, and the GitHub repository — as of 2026-07-13, re-confirmed 2026-07-14. That scan was expressly non-exhaustive, and the negative is dated, not universal. The paper's own failure conditions are the place to start if you want to argue against it.

## Files

- `Lee-Odinson_2026_Peership-Thesis_v1.0.pdf` — frozen published preprint.
- `source/` — editable source. Holds the Markdown source, `Lee-Odinson_2026_Peership-Thesis_v1.0.md`.
- `arxiv/` — the arXiv submission package (see below).

### The `arxiv/` package

Three files, and they are coupled:

| File | Role |
| --- | --- |
| `main.tex` | The LaTeX source. |
| `main.bbl` | The pre-compiled bibliography, pulled in by `\input{main.bbl}` in `main.tex`. |
| `references.bib` | The cited subset of the corpus bibliography. |

Two things follow, and both are easy to break:

1. `main.tex` uses `\input{main.bbl}` rather than `\bibliography{...}`. The two basenames must therefore stay matched — renaming either file, or renaming one without the other, breaks the build. arXiv compiles the `.bbl` directly and does not run BibTeX.
2. `references.bib` is **not read at compile time**. It is the cited subset of [`apparatus/peership_sources.bib`](../../apparatus/peership_sources.bib), retained for provenance and for anyone who wants to regenerate the bibliography. Editing it alone changes nothing in the output; the compiled bibliography lives in `main.bbl`.

## Companion

A derivative one-page companion, **The Peership Theses**, is published alongside this paper: [`corpus/companions/peership-theses/`](../companions/peership-theses/). It is not a sixth corpus paper. It has no DOI of its own — it is deposited inside Zenodo record 21359124 and is cited by this paper's DOI.

## A note on the Zenodo record

Record 21359124 contains three files: `Lee-Odinson_2026_Peership-Thesis_v1.0.pdf`, `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0.pdf`, and `Peership_v1.0_complete_release.zip` (which bundles the apparatus). The author's local deposit metadata sheet had described eleven separately-uploaded files. The archived record controls; nothing was changed. Recorded as **D1** in [`VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md).

## Citation

> Lee-Odinson, D. (2026). *The Peership Thesis: A Constitutional Research Program for Human–Machine Relations* (v1.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21359124

Cite the concept DOI ([10.5281/zenodo.21359123](https://doi.org/10.5281/zenodo.21359123)) only when you intend to refer to all versions of the paper rather than to v1.0 specifically.
