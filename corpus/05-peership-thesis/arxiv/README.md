# arXiv source package — *The Peership Thesis* v1.0

The compilable LaTeX source for the canonical paper, arranged as an arXiv submission.

## Files

| File | Role |
|---|---|
| `main.tex` | The paper. Compiles under `pdflatex` and `xelatex`. |
| `main.bbl` | The formatted bibliography, pulled in by `\input{main.bbl}` at the end of `main.tex`. |
| `references.bib` | The cited subset of the corpus bibliography (38 entries). |

## Two things that will break the build if you overlook them

**The basenames are coupled.** `main.tex` ends with `\input{main.bbl}` — a literal
filename, not a `\bibliography{}` directive. Rename one of the two and you must rename
the other. (In the deposited LaTeX package both files are named `peership_thesis.*`;
they were renamed to `main.*` here to match arXiv's convention, and the `\input` line
was updated to match. That is the only edit made to the source.)

**`references.bib` is not read at compile time.** The bibliography is pre-formatted in
`main.bbl`, which is what arXiv expects — arXiv does not run BibTeX for you. The `.bib`
is included so that a reader can see the underlying metadata and so the citation keys
resolve against the canonical database. Editing `references.bib` alone will change
nothing about the rendered output; the `.bbl` must be regenerated.

## Compiling

```sh
pdflatex main.tex
pdflatex main.tex   # second pass resolves cross-references
```

No BibTeX pass is required.

## Relationship to the other copies of this paper

There are three renderings of the same frozen text, and they are not interchangeable
as citation targets:

- [`../Lee-Odinson_2026_Peership-Thesis_v1.0.pdf`](../Lee-Odinson_2026_Peership-Thesis_v1.0.pdf) — the **frozen published preprint**. This is the artifact deposited on Zenodo and the one to cite: <https://doi.org/10.5281/zenodo.21359124>.
- [`../source/Lee-Odinson_2026_Peership-Thesis_v1.0.md`](../source/Lee-Odinson_2026_Peership-Thesis_v1.0.md) — the plain-text source.
- this directory — the LaTeX source package.

The PDF controls. If a rendering ever disagrees with it, the deposited PDF is the paper.

## Status

The paper has **not** been submitted to arXiv as of the v1.0.0 corpus release. This
package is kept submission-ready. If it is submitted, the arXiv identifier should be
added to Zenodo record 21359124 as a related identifier, and recorded in
[`../../../VERSION_MANIFEST.md`](../../../VERSION_MANIFEST.md) — a new rendering does not
create a new work, and it does not mint a new DOI.

## Licence

CC BY 4.0, as with all scholarly material in this repository. See
[`../../../LICENSE`](../../../LICENSE).
