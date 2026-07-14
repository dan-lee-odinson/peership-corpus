# The Peership Apparatus

**Maintainer:** Dan Lee-Odinson (ORCID [0009-0009-9504-0796](https://orcid.org/0009-0009-9504-0796))
**Licence:** CC BY 4.0
**Apparatus state (2026-07-14):** `.bib` revision 1.3 · sourcebook and ledger carry a v1.2 header with a revision 1.3 (deposit day) note.

This directory holds the scholarly apparatus of the Peership corpus: the bibliography, the annotated classification of every source, and the claim-by-claim provenance ledger. Its purpose is to make the corpus **auditable** — to expose its debts, its disagreements, and its weak points so that a hostile reader can check it, correct it, or defeat it.

The apparatus is not an argument. It is infrastructure for testing one. Nothing in this directory is evidence that Peership is an established school; a bibliography can show that sources were collected with care, and a ledger can show they were used with discipline, but neither can show that anyone other than the author has taken the program up. In the sources scanned on 2026-07-13 (re-confirmed 2026-07-14; expressly non-exhaustive), no such uptake was identified — see [`search_protocols/uptake_scan.md`](search_protocols/uptake_scan.md).

---

## The three files and their roles

| File | Role | State |
|---|---|---|
| [`peership_sources.bib`](peership_sources.bib) | **Machine-readable source of truth.** One citation key per work, with full metadata, DOIs, versions, and access dates. 161 entries. Where the three files disagree about a work's metadata, the `.bib` is authoritative and the others are the ones in error. | Revision 1.3 (2026-07-14) |
| [`peership_sourcebook.md`](peership_sourcebook.md) | **Classification and annotation.** The research map: which category each source falls into, what it argues, how the corpus uses it, what it does *not* establish, and what stands against it. Also holds the paper-to-source index, the independent-uptake tracker (§5), and the historical corrections log inherited from the v4 compendium (Appendix C). | v1.2 header + revision 1.3 (deposit-day) note |
| [`peership_claim_ledger.md`](peership_claim_ledger.md) | **Claim-level provenance and counterevidence.** Roughly 71 logged claims, each recorded against a 12-field schema, including what would count *against* the claim. | v1.2 header + revision 1.3 (deposit-day) note |

Two further files sit alongside them: [`corrections_log.md`](corrections_log.md) (corrections made from the v1.0.0 corpus release onward) and [`search_protocols/`](search_protocols/) (the dated, open record of the negative scans the corpus relies on).

**On the version numbering.** The sourcebook and the ledger were revised on deposit day without a header bump: each carries `Version: 1.2` in its front matter *and* a "Revision 1.3 (deposit day, 2026-07-14)" line recording what closed. Both descriptions are accurate; neither file should be silently cited as "v1.3." The `.bib` header does say revision 1.3. This is a real inconsistency in the frozen deposit and it is recorded rather than papered over.

---

## The classification scheme is a boundary, not a family tree

The sourcebook places every source in exactly one primary category. The point of the scheme is to make annexation impossible: a source is in the **Direct Peership corpus** category **only if it formulates or expressly adopts political Peership**. In practice that means Lee-Odinson only. Everything else in the bibliography is a debt, a neighbour, a rival, or a tool.

| # | Category | Test for membership |
|---|---|---|
| 1 | Direct Peership corpus | Formulates or expressly adopts political Peership. (Lee-Odinson only.) |
| 2 | Intellectual foundations | Supplies concepts the corpus uses directly — non-domination, the all-subjected principle, legality, commons governance, consent, emergency power, legitimate coercion, and the classical and literary material the arguments run on. |
| 3 | Precursors & convergent approaches | Earlier or independent work approaching partnership, mutuality, or machine standing **without asserting the Peership thesis**. |
| 4 | Adjacent research programs | Alignment, AI welfare, cooperative AI, AI rights, pluralistic alignment, relational ontology, human–AI intimacy, Constitutional AI. |
| 5 | Critics & incompatible accounts | Deny machine subjecthood, political membership, relational reciprocity, or the feasibility of shared governance. |
| 6 | Implementation hypotheses | ISONOMIA and any later institutional design attempting to instantiate some Peership principles. |

Two rules enforce the boundary. The **relationship vocabulary** requires the sourcebook to say, for each external source, whether it *supports*, *complicates*, or *opposes* a specific corpus claim — and forbids the assertion that two works "investigate the same phenomenon" unless both a shared object of inquiry and the important disagreements have been shown. The **analytical-label rule** requires that terms belonging to the corpus's own apparatus (*Command*, *Servitude*, *the Dependent Bargain*, *cognitive peership*) be marked **[analytical classification]** wherever the cited author did not use them, and never attributed to that author.

Categories 3 and 4 are where most of the bibliography lives, and they are where the corpus is most exposed to the charge of overclaiming. They are also the categories the reader should audit first.

---

## The claim ledger: twelve fields, seven namespaces

The ledger is the discipline artifact. For every material factual or attributed claim in the corpus it records twelve fields:

| Field | Content |
|---|---|
| Claim ID | Stable identifier |
| Corpus location | Paper · version · section/note |
| Claim | Exact claim or normalized form |
| Source | Citation key(s), resolving in `peership_sources.bib` |
| Pinpoint | Page, §, figure, or timestamp |
| Evidence | Short quotation or accurate paraphrase |
| Source type | primary-statement / empirical-study / scholarship / preprint / institutional-publication / primary-text / journalism |
| Status | published / peer-reviewed / preprint / forthcoming / superseded / disputed / withdrawn |
| Evidentiary strength | What the source establishes — **and what it does not** |
| Counterevidence | Contrary source or unresolved dispute |
| Verification | Verifier · date checked |
| Revision history | Corrections or changes affecting the claim |

The "evidentiary strength" and "counterevidence" fields are the load-bearing ones. A ledger entry that only says what a source supports has failed its purpose.

Claim IDs are stable and namespaced by the paper the claim lives in:

| Namespace | Section |
|---|---|
| `CL-F#` | Flagged verification failures (errors inherited from the v4 compendium and corrected) |
| `CL-D#` | Disputed or resolved metadata (DOIs, versions, mappings) |
| `CL-G#` | *Gods and Slaves* |
| `CL-P#` | *Peership* |
| `CL-I#` | *The Isonomia Commons* |
| `CL-C#` | *Constitution, Not Cage* |
| `CL-T#` | *The Peership Thesis* |

Verifier legend: `web-2026-07-13` means independently resolved online on that date; `author-pinned` means pinned in the corpus's reference notes but not independently re-verified (typically pre-web books and primary texts); `corpus-internal` means a claim about the corpus's own artifacts.

Coverage is **gate-complete plus key claims**, not exhaustive of every sentence: every direct quotation, every numerical or empirical claim, every priority or superlative claim, every flagged verification failure, and the major attributed positions. Where a pinpoint is still coarse, the ledger says so rather than hiding it — CL-P19 (Sutton, pinned at talk level, timestamp pending) and CL-G2 (Crowley 1904, page pending) are the two open cases, and CL-F7 (the Hinton statements) is open pending individually citable interviews.

---

## The synchronization rule

**A correction to any one of the three files must be mirrored across every file it affects.** This is not a nicety of housekeeping; it is the condition under which the apparatus is worth anything. A DOI corrected in the ledger and left wrong in the `.bib` produces a corpus that cites two different works under one key.

Concretely: citation keys used in the sourcebook and the ledger must resolve in the `.bib`; claim IDs used in the sourcebook must resolve in the ledger; and a change to a source's metadata, status, or classification propagates to all three. Corrections are then logged in [`corrections_log.md`](corrections_log.md) and reflected in the repository's [`CHANGELOG.md`](../CHANGELOG.md). The ledger's revision-history column is the canonical per-claim record of what changed and why.

---

## Four disciplines the apparatus enforces

### 1. Self-citation is corpus architecture, not evidence of independent acceptance

The five works cite each other heavily; each is a sequel to the last. That internal cross-referencing is **architecture**, not uptake, and it is deliberately excluded from the independent-uptake tracker. The same goes for the corpus's self-published footprint — the Zenodo deposits, the `isonomia-path-a` repository, the PhilArchive presence, the Substack variant of *Gods and Slaves*. That is **footprint, not uptake**. Uptake means external citation, published criticism, adoption of the definitions, or a rival implementation by someone else. None has been found. See [`search_protocols/uptake_scan.md`](search_protocols/uptake_scan.md).

### 2. ISONOMIA is classified as an implementation hypothesis, not as argumentative corpus

*The Isonomia Commons* appears in the sourcebook's Part A because the corpus author wrote it, but it is **classified as a category-6 implementation hypothesis**. The apparatus is built to hold rival designs that accept Peership's principles and reject ISONOMIA's mechanisms.

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

The simulation work pinned in the ledger establishes sampled launch-economy behaviour and nothing more. It does not establish constitutional legitimacy, does not validate Peership, and nothing is live or production-validated. The constitutional properties — admission, non-domination, independent enforcement, recognition — were **not** simulated.

### 3. Dated negative claims keep their dates and their limitations

Several claims the corpus relies on are negatives: no independent uptake was found; no qualifying instrument was found; no implemented fork analogue was found. Each is **a dated, non-exhaustive scan of named sources**, and each is scoped in the text that relies on it.

**A dated, non-exhaustive scan must never be converted into a universal claim.** "No independent uptake was identified in the sources scanned on 13 July 2026" is a finding. "There is no independent uptake" is not, and neither is "no such instrument exists." The qualifiers — *in the sources searched*, *known to this author*, *among the materials reviewed in the apparatus* — are load-bearing and are to survive every paraphrase, every summary, and every future edit. The scans are recorded in [`search_protocols/`](search_protocols/), including the honest admission that the original query strings were never archived, so those scans are not reproducible as run.

### 4. The apparatus is living; the papers are frozen

The five corpus papers are archived Zenodo deposits. They cannot be edited, and they are not edited: where a frozen paper contains an error, the error stays in the paper and the correction is recorded here. The apparatus is the opposite — it is versioned, correctable, and expected to change. Errors found in it should be reported, not tolerated.

Corrections are proposed through this repository's issue tracker: **<https://github.com/dan-lee-odinson/peership-corpus/issues>**. Note that the archived Zenodo README and the sourcebook's own Appendix D still direct correspondents to the `isonomia-path-a` repository, because this corpus repository did not exist at deposit. That supersession is recorded in [`corrections_log.md`](corrections_log.md); the frozen deposits cannot be edited to point here.

---

## What the apparatus does not do

It does not establish that present AI systems are conscious, persons, or peers — the corpus does not claim this. It asks what institutions would be required *if* credible candidates for moral and political standing emerge. It does not establish that Peership is uniquely correct, technically feasible, or safe. It does not establish that a school exists.

A hostile but informed reader should be able to answer, from these files alone: what exactly Peership claims; which external sources support, complicate, or oppose each claim; how strong and current the evidence is; and what another researcher would need in order to challenge or extend the program. Where they cannot yet, the gap is named rather than hidden.
