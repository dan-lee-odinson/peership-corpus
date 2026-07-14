# THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets

**Author:** Dan Lee-Odinson
**Version:** v1.1
**Status:** Preprint
**Exact-version DOI:** [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917)
**Concept DOI:** [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479)
**License:** CC BY 4.0

## The implementation firewall

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

This firewall governs every reading of this paper. Nothing below weakens it.

## Role in the corpus

Paper III works out **one** institutional implementation hypothesis: a constitutional design for autonomous agent labour markets. It exists to show that the normative argument of [Paper II](../02-peership/) can be given concrete institutional shape and thereby made criticisable — a design that can fail in specifiable ways is more useful than a principle that cannot. It is a specification, not a proof.

What it does **not** establish: it does not prove Peership, is not the only permitted implementation of it, and is not entailed by it. Its simulations do not establish constitutional legitimacy, and no part of it is live or production-validated. A design that worked would not vindicate Peership; a design that failed would not refute it.

## Empirical results and their limits

The paper's empirical results come from a **45,000-run parameter sweep** carried out in the separate ISONOMIA repository, not in this one. No code or simulation data is duplicated here.

The evidence is pinned to a single release:

| Item | Value |
| --- | --- |
| Repository | [dan-lee-odinson/isonomia-path-a](https://github.com/dan-lee-odinson/isonomia-path-a) |
| Evidence-bearing release | v1.0.0 (2026-07-10) |
| Git commit | `ba3ddb5` (full: `ba3ddb51dbcc147def470b7af1eaddef6f349157`) |
| Exact-version software DOI | [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) |
| Software concept DOI | [10.5281/zenodo.21287288](https://doi.org/10.5281/zenodo.21287288) |

A later documentation release (v1.1.0, DOI [10.5281/zenodo.21348073](https://doi.org/10.5281/zenodo.21348073), commit `def8f29`) changed documentation and claim language only. No code, simulation, data, or result changed, and the empirical evidence remains pinned to v1.0.0 / `ba3ddb5`.

**Hard limit on what the simulations show.** They establish **sampled launch-economy behaviour only**. They do **not** establish constitutional legitimacy, they do **not** validate Peership, and nothing in them is live or production-validated. Any claim beyond sampled launch-economy behaviour is unsupported by this evidence.

For the corpus's account of the relationship between the paper and the implementation repository, see [`implementations/isonomia.md`](../../implementations/isonomia.md).

## A note on the DOIs

The identifiers in the header above are the API-verified ones. One subtlety must be flagged, because the paper's own front matter gets it wrong:

- [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) is the **concept (all-versions) DOI**.
- [10.5281/zenodo.21338480](https://doi.org/10.5281/zenodo.21338480) is the **v1.0 exact-version DOI**, not a concept DOI.
- [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) is the **v1.1 exact-version DOI** — the version archived here.

The frozen PDF's front matter mislabels ...21338480 as a concept DOI. The frozen artifact has not been altered; ledger entry **CL-D3** resolved the discrepancy in favour of the Zenodo API, and this README records the correct reading. The separate `isonomia-path-a` repository's manifest still carries the old label; correcting it is out of scope for this corpus. See [`VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md) (D5).

## Review status — read this before weighting the paper's claims

**This is the one paper in the corpus with no adversarial-review document.**

Papers I, II, IV and V each went through their own adversarial review cycle, and the reviews and disposition records are published in [`reviews/`](../../reviews/). This paper did not. It was condensed from the ISONOMIA **whitepaper**, which had already been through an extensive development and review process upstream — that whitepaper is why ISONOMIA sits third in the canonical reading order — so the review pass on the preprint itself was **short** and produced no standalone review document.

What scrutiny it did receive was of the specification and its evidence, not of the essay. That upstream review is real and it is **publicly evidenced**, though in the implementation repository rather than here: the whitepaper's changelog carries an entry titled *"adversarial-review response"*; the launch spec's changelog records a claim-discipline pass that restated overclaims in sampled-point terms; `CALIBRATION.md` carries the matching revision note; and `DECISIONS.md` #35 records a spec↔code divergence in which the **spec was corrected rather than the code**. The review documents themselves are held pending that repository's scheduled release.

**None of that is a substitute for adversarial review of this paper, and none of it is offered as one.** Simulation evidence is not paper review, and those simulations establish sampled launch-economy behaviour only.

A reader comparing the five papers should know that **this one received the least independent adversarial scrutiny as a paper**, and weight its claims accordingly. The full account — including what is verifiable today and what is not — is in [`reviews/REVIEW_PROVENANCE.md`](../../reviews/REVIEW_PROVENANCE.md).

## Files

- `Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf` — frozen published preprint. The byte content is identical to the Zenodo file, which is named `Lee-Odinson_2026_Isonomia-Commons_v1_1_preprint_UPDATE.pdf`; the repository copy is renamed under the filename-hygiene rule (see [`VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md), D2).
- No editable source is published for this paper; the frozen PDF is the artifact.

## Citation

> Lee-Odinson, D. (2026). *THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets* (v1.1) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21343917

Cite the concept DOI ([10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479)) only when you intend to refer to all versions of the paper rather than to v1.1 specifically. When citing the simulation evidence, cite the software release — [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) — not this paper alone.
