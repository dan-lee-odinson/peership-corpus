# Contributing

This repository exists to be argued with.

Peership is a **candidate** constitutional research program, not an established school with independent uptake. It has one author, no institutional home, and no confirmed readership beyond its own footprint. A program in that position needs correction, criticism, extension, and audit more than it needs agreement, and this repository is the apparatus that makes those things possible.

Before contributing, read [`README.md`](README.md) for what the corpus is, [`PROVENANCE.md`](PROVENANCE.md) for who is responsible for it, and [`VERSION_MANIFEST.md`](VERSION_MANIFEST.md) for the known discrepancies you do not need to report again.

---

## 1. What can change, and what cannot

**The papers cannot be edited.** The five works are archived deposits on Zenodo. Each exact-version DOI resolves permanently to the bytes deposited under it. The PDFs in [`corpus/`](corpus/) are byte-identical copies kept here for convenience; they are not the authoritative artifacts, and they are not editable in any sense that matters. Papers I–IV have no editable source at all. If a frozen paper contains an error, the remedy is to *record* it, not to *repair* it.

**What can change:**

| Correctable | Where |
|---|---|
| The apparatus (bibliography, sourcebook, claim ledger) | [`apparatus/`](apparatus/) |
| Search protocols | [`apparatus/search_protocols/`](apparatus/search_protocols/) |
| The corrections log | [`apparatus/corrections_log.md`](apparatus/corrections_log.md) |
| READMEs and repository documentation | throughout |
| Metadata (DOIs, versions, dates, file manifests) | [`VERSION_MANIFEST.md`](VERSION_MANIFEST.md), `CITATION.cff`, apparatus |
| Links to rival or successor implementations | [`implementations/`](implementations/) |

An error in a frozen paper is therefore corrected by an entry in the corrections log and a propagated fix in the apparatus, leaving an honest trail from the published mistake to its correction. A reader who finds the error in the PDF and the correction in the apparatus is the reader this design is for.

---

## 2. Open an issue first

Use one of the four issue forms. Each exists because a different kind of contribution needs a different kind of evidence.

| Form | Use it when |
|---|---|
| [Factual or citation error](.github/ISSUE_TEMPLATE/factual_or_citation_error.yml) | Something is verifiably wrong: a misquotation, a misattributed argument, a broken or incorrect DOI, a wrong date, a source that does not say what it is cited as saying, a mismatch between the three apparatus files. Bring the source. |
| [Conceptual objection](.github/ISSUE_TEMPLATE/conceptual_objection.yml) | An argument fails: an equivocation, a missing premise, a counterexample to a claim, a failure condition the program has not confronted, a case where the corpus's own claim discipline is violated by its own text. Bring the argument. |
| [Source proposal](.github/ISSUE_TEMPLATE/source_proposal.yml) | A work should be in the bibliography and is not — a prior formulation, a rival position, a disconfirming literature, a tradition the corpus has ignored. Say what the source *does to the argument*, not merely that it is relevant. |
| [Implementation proposal](.github/ISSUE_TEMPLATE/implementation_proposal.yml) | You have built, or intend to build, an institutional design that answers the Peership constraints — including one incompatible with ISONOMIA. |

All four forms live in [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/).

Open the issue before the pull request. Nearly every worthwhile contribution here needs its scope agreed first, because a correction that touches a source is never a one-file change (see §3).

---

## 3. The synchronization rule

Three apparatus files are a single logical record kept in three formats. They must not drift.

- [`apparatus/peership_sources.bib`](apparatus/peership_sources.bib) — the canonical machine-readable source of truth (revision 1.3, 2026-07-14; 161 BibTeX entries).
- [`apparatus/peership_sourcebook.md`](apparatus/peership_sourcebook.md) — annotated bibliography and research map (v1.2 header, revision 1.3 (deposit day)).
- [`apparatus/peership_claim_ledger.md`](apparatus/peership_claim_ledger.md) — claim-level provenance (v1.2 header, revision 1.3 (deposit day); roughly 71 claims, with IDs of the form CL-F#, CL-D#, CL-G#, CL-P#, CL-I#, CL-C#, CL-T#).

> **Rule.** A correction that touches a source must be mirrored across all three — `peership_sources.bib`, `peership_sourcebook.md`, and `peership_claim_ledger.md` — and logged in [`apparatus/corrections_log.md`](apparatus/corrections_log.md).

A pull request that fixes a BibTeX entry and leaves the sourcebook annotation and the claim ledger describing the old, wrong source has not fixed anything; it has hidden the error in a second place. Where the `.bib` and the Markdown disagree, the `.bib` is canonical and the Markdown is what needs fixing.

Every correction gets a dated entry in the corrections log: what was wrong, what it now says, who reported it, and which claim IDs are affected. The log is append-only. Corrections are not quietly absorbed.

---

## 4. Claim discipline expected of contributors

The corpus holds itself to a discipline of claim-making, and contributions are held to the same one. This is not a style preference. Most of the ways a young research program embarrasses itself are ways of overclaiming, and the discipline is what stops it.

**Dated negatives stay scoped.** The corpus's uptake baseline is: *"No independent uptake identified"* — verified 2026-07-13, re-confirmed with no change 2026-07-14, across web, PhilPapers, Zenodo, and the GitHub repository. That claim is expressly **non-exhaustive** and it is **dated**. It does not become "nobody has ever cited this," and it does not become permanent by repetition. If you cite the baseline, carry its date and its scope with it. If you have evidence that overturns it, that is a factual-error issue and it is welcome.

Note the corresponding distinction between *footprint* and *uptake*. Five Zenodo deposits, an implementation repository, a PhilArchive presence, and a Substack variant of *Gods and Slaves* are the author's own footprint. None of them is uptake by anyone else.

**Convergent independent work is parallel invention, not uptake.** Unverified leads exist — for instance, work applying republican liberty to AI that does not cite this corpus. If such convergence is confirmed, it is *parallel invention*: evidence that the problem is real and the approach is not idiosyncratic, and nothing more. It is not uptake, it is not endorsement, it is not influence, and it must not be cited as a source of the corpus. Contributors who find convergent work should say plainly that it is convergent and that it does not cite the corpus.

**Self-citation is architecture, not acceptance.** The five works cite one another because they are one program with a canonical reading order. The Thesis consolidates the essays; ISONOMIA implements what *Peership* argues for. That internal citation graph is structural. It is not evidence that the program has been received, and no contribution may present it as such.

**The claims the repository must never imply.** No contribution may assert or insinuate:

- that present AI systems are conscious, persons, or peers;
- that model self-reports establish consciousness or political agency;
- that intelligence, capability, usefulness, or power creates an entitlement to rule or vote;
- that moral concern automatically entails political membership;
- that welfare protection is already Peership;
- that consultation is equivalent to co-authorship;
- that every admitted entity automatically receives an equal franchise;
- that Peership means unrestricted autonomy or immunity from legitimate safety constraints;
- that alignment, safety engineering, or containment is inherently illegitimate;
- that Peership has been proved uniquely correct or technically feasible;
- that ISONOMIA has solved or validated Peership;
- that ISONOMIA's simulations validate constitutional legitimacy.

The affirmative framing to use instead: the corpus does not claim present AI systems are conscious, persons, or peers; it asks what institutions would be required **if** credible candidates for moral and political standing emerge.

**The thesis, when you state it, is stated in full.** Where the canonical thesis is asserted, reproduce this compact form exactly:

> When an artificial entity has interests capable of being wronged, can understand and answer to public norms, and is enduringly governed by a shared basic structure without feasible exit, it acquires a defeasible claim to contestatory membership in that structure. Full Peership adds a consequential share in shaping and revising the basic rules.

Never shorten it to "anything governed deserves rights." The three antecedent conditions and the *defeasible* character of the conclusion must survive every paraphrase, including in issue titles, commit messages, and PR descriptions. An objection aimed at the shortened version is aimed at a claim nobody made, and will be redirected to the real one.

---

## 5. What will be rejected

- **Edits to the frozen PDFs.** They are archived deposits. A PR that modifies bytes under [`corpus/`](corpus/) will be closed on sight. Report the defect instead; it will be logged.
- **Claims that present AI systems are conscious, persons, or peers.** This includes contributions that argue for it, contributions that assume it, and contributions that smuggle it in through model self-reports or through the fluency of model output. The corpus's whole method depends on this line holding. Arguments about the *conditions under which* standing could arise are the subject matter and are welcome; assertions that the conditions are already met are not.
- **Treating ISONOMIA as proof of Peership.** The firewall is not negotiable:

  > ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

  The 45,000-run parameter sweep establishes sampled launch-economy behaviour only. It does not establish constitutional legitimacy, does not validate Peership, and nothing in it is live or production-validated. Contributions that treat the simulations as normative validation will be rejected regardless of how favourable to the program they are. The friendly version of this error is worse than the hostile version, because it is the one the author is tempted to accept.

Also rejected: contributions written in a marketing voice; contributions that universalise the dated negative; contributions that present convergent work as uptake; and pull requests that break the synchronization rule.

---

## 6. Rival implementations are welcome

Actively welcome. **Peership does not entail ISONOMIA.**

If Peership is right, there are many institutional designs that could satisfy it, and the corpus has no interest in pretending its one worked example is the only one — that pretence is precisely how a research program collapses into a product. A rival design that meets the constitutional constraints in *Constitution, Not Cage* and rejects ISONOMIA's mechanisms entirely is a contribution to the program, not an attack on it. A design that shows the constraints cannot be jointly satisfied is a more valuable contribution still: that is a failure condition, and the program has committed itself to naming its failure conditions.

Open an [implementation proposal](.github/ISSUE_TEMPLATE/implementation_proposal.yml). Accepted implementations are **linked** from [`implementations/`](implementations/), not vendored into this repository. Code and data belong in their own repositories, under their own licences, with their own releases and their own archival identifiers. The ISONOMIA implementation itself lives at <https://github.com/dan-lee-odinson/isonomia-path-a> and is linked, never duplicated here.

---

## 7. Labels

| Label | For |
|---|---|
| `factual-error` | Verifiable errors of fact, date, DOI, version, or attribution |
| `citation` | Bibliography and citation defects; source-to-claim mismatches |
| `conceptual-objection` | Arguments against the program's claims or its coherence |
| `source-proposal` | Works proposed for the bibliography |
| `implementation` | Implementation designs, including rivals to ISONOMIA |
| `apparatus` | Changes to the three synchronized files, protocols, or the corrections log |
| `metadata` | DOIs, versions, manifests, `CITATION.cff`, file naming |
| `question` | Requests for clarification about scope, claims, or process |

---

## 8. Pull requests

1. Open an issue first, using the right form.
2. Branch from `main`; keep the change to one issue's worth of scope.
3. Obey §3 if a source is touched: all three apparatus files, plus the corrections log.
4. Reference the affected claim IDs (CL-F#, CL-D#, CL-G#, CL-P#, CL-I#, CL-C#, CL-T#) where the ledger is involved.
5. Write for a skeptical scholarly reader: plain sentences, no hype, no marketing voice.
6. Use relative Markdown links that resolve on GitHub from the file's own location.
7. Do not edit anything under [`corpus/`](corpus/).

Reviews in [`reviews/`](reviews/) are historical records of the release gate. They are not editable working documents and are not authoritative: the frozen papers and the synchronized apparatus control.

---

## 9. Licensing of contributions

**Contributions to scholarly material are accepted under [CC BY 4.0](LICENSE).**

That covers everything you are likely to contribute: the apparatus, the bibliography, the sourcebook, the claim ledger, the corrections log, the search protocols, the READMEs, the metadata, and the documentation. By opening a pull request you agree that your contribution is licensed CC BY 4.0 and that you have the right to license it.

The Apache-2.0 [`LICENSE-APACHE`](LICENSE-APACHE) file is reserved for executable code and build scripts. **This repository currently contains no executable code.** The papers are never Apache-licensed; the file-level licence table in the README controls.

---

## 10. Responsibility

Dan Lee-Odinson ([ORCID 0009-0009-9504-0796](https://orcid.org/0009-0009-9504-0796)) is the sole author of the corpus and the party answerable for its claims. He is also the person who has to be talked out of his own errors, which is what this file is for. Contributors are credited in the corrections log for corrections adopted; contribution to the apparatus is not authorship of the works. See [`PROVENANCE.md`](PROVENANCE.md) §4.
