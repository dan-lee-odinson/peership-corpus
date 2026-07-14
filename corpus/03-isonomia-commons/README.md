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

This record has **three DOIs. All three are valid and permanent. None is stale.** They identify different objects:

| DOI | Identifies | Resolves to |
|---|---|---|
| [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) | The **concept (all-versions)** DOI — the work as a whole | Always the latest version |
| [10.5281/zenodo.21338480](https://doi.org/10.5281/zenodo.21338480) | The **v1.0 exact-version** DOI | Permanently, v1.0 |
| [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) | The **v1.1 exact-version** DOI — the version archived here | Permanently, v1.1 |

One subtlety, because the paper's own front matter gets it wrong: it captions `…21338480` the "concept DOI." It is not — it is the v1.0 version DOI. **The identifier is fine; only the caption is wrong.** Cite `…21338480` freely whenever you mean v1.0 specifically; just never call it a concept DOI. The frozen artifact has not been altered. Ledger entry **CL-D3** resolved this against the Zenodo API, and this README records the correct reading. The `isonomia-path-a` manifest carries the same caption error; that repository is frozen, so the fix travels with its next release. See [`VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md) (D5).

## Review status — read this before weighting the paper's claims

This paper was **reviewed hard, but the least *checkably* of the five.** Both halves of that sentence matter.

**It was reviewed hard.** The whitepaper this preprint condenses went through **five documented formal adversarial cycles**, and they cost the design its strongest claims: minted transferable credit was removed in favour of mutual credit; "individually proven" became "individually precedented, composition unproven"; sovereignty claims were narrowed; legal and infrastructure dependence were admitted; and the simulation kill-criterion was **rebuilt four times** because it kept failing. The preprint then went through a publication audit that caught substantive claim-discipline failures in the paper itself — it had called ISONOMIA the design "at the center" of the corpus and said it "instantiates Peership," both of which v1.1 corrected, along with replacing continuous-region stability language with sampled-point claims. The audit trails are published in [`reviews/03-isonomia-commons/`](../../reviews/03-isonomia-commons/).

**But it is the least checkable.** Three deficits, relative to papers I, II, IV and V:

1. **Its review prompt was never preserved.** What is published is an explicit *reconstruction*. Papers II and V publish their **actual, verbatim** prompts, so a reader can confirm the reviewer was told to attack. For this paper, they cannot.
2. **No verbatim review document is published.** The raw notes are held pending the ISONOMIA repository's scheduled release. What exists here is a summary of a process, not the adversary's own text.
3. **Most of that scrutiny landed on the design and the package, not on the essay as an argument.**

What *is* independently checkable today: the dispositions are public and dated in the implementation repository — the whitepaper changelog's *"adversarial-review response"* entry, the launch spec's claim-discipline pass, `CALIBRATION.md`'s revision note, and `DECISIONS.md` #35, where a spec↔code divergence was resolved **in the code's favour**.

**Simulation evidence is not paper review**, and none of it is offered as such. Weight this paper's claims accordingly. The full account is in [`reviews/REVIEW_PROVENANCE.md`](../../reviews/REVIEW_PROVENANCE.md).

## Files

- `Lee-Odinson_2026_Isonomia-Commons_v1.1_preprint.pdf` — frozen published preprint. The byte content is identical to the Zenodo file, which is named `Lee-Odinson_2026_Isonomia-Commons_v1_1_preprint_UPDATE.pdf`; the repository copy is renamed under the filename-hygiene rule (see [`VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md), D2).
- No editable source is published for this paper; the frozen PDF is the artifact.

## Citation

> Lee-Odinson, D. (2026). *THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets* (v1.1) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21343917

Cite the concept DOI ([10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479)) only when you intend to refer to all versions of the paper rather than to v1.1 specifically. When citing the simulation evidence, cite the software release — [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) — not this paper alone.
