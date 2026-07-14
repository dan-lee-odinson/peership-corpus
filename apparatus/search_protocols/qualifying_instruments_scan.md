# Qualifying-Instruments Scan — A Rights Floor Enforceable Against a Maker

**DATED OPEN INFRASTRUCTURE.** This file records a scan that was actually run, on a named date, over named source types, with a stated result and stated limits. It is **not** a reproducible protocol for the scan as run. See [The query strings were not archived](#the-query-strings-were-not-archived), which is the most important section in this file.

**Supports:** the *Peership Thesis* §4 scoped negative (no qualifying instrument **in the sources searched**); the reused §"Repertoire" negative carried from *Peership* (no implemented public trigger **known to this author**). Ledger **CL-T3** and **CL-T7**.
**Scan date:** 2026-07-13. **Re-confirmed:** 2026-07-14 (deposit day), no change.
**Run by:** Dan Lee-Odinson (maintainer).

---

## What the scan was looking for

A **qualifying instrument**: a public instrument — a law, a regulation, a standard, a published corporate or laboratory policy — that offers an artificial system a **rights floor enforceable against its maker**. Two properties are jointly required, and neither alone qualifies:

1. **A floor of protections that is not at the maker's discretion.** A voluntary welfare commitment that the maker may revise or withdraw at will is not a floor; it is a policy.
2. **Enforceability against the maker** — some route by which the protected party, or someone with standing to act for it, can compel compliance. A commitment enforceable only by the party that wrote it is not enforceable in the relevant sense.

The companion negative concerns a **public trigger**: a published, implemented rule that would require a transition **from owned artifact to contestable status on evidence of subjecthood** — that is, a stated threshold at which the legal or institutional character of the system changes, rather than a promise to consider the question.

Both are institutional claims about what has been *implemented*, not about what has been *proposed*. Proposals exist; the scholarly literature cited in the sourcebook contains several. The negative is about instruments in force.

---

## Result

**None found.** No qualifying instrument was identified in the sources searched, and no implemented public trigger of the kind described was identified.

### Results table (2026-07-13; re-confirmed 2026-07-14, no change)

| Source type searched | What was looked for | Result |
|---|---|---|
| **Laboratory** — published AI-developer policies, model cards, system cards, welfare commitments | A protection floor a developer could not unilaterally withdraw; a stated status trigger | None found. What exists is discretionary: welfare commitments, consultation, and end-conversation affordances, all revisable by the developer. |
| **Governmental** — statutes, regulations, and public consultations | An enforceable floor for an artificial system against its maker | None found. Regulation addresses risk to humans, product safety, and liability of makers to third parties — not obligations owed **to** the system. |
| **Standards-body** — published technical and governance standards | A conformance requirement establishing enforceable status or a subjecthood trigger | None found. |
| **Scholarly** — legal and philosophical literature on AI rights, personhood, and welfare | An implemented instrument (as distinct from a proposal for one) | None found. The literature contains proposals and arguments; it identifies no instrument in force. |

The evidentiary asymmetry is worth stating plainly: the scan found a great deal of *adjacent* material — welfare programs, safety commitments, consultative constitutions, personhood proposals — and none of it qualified. That is the finding. The gap the corpus points at is a gap between what is discussed and what is enforceable.

---

## The scope qualifiers are load-bearing

Two qualifiers appear in the corpus text and **must be retained in every restatement**:

- **"in the sources searched"** (*Peership Thesis* §4)
- **"known to this author"** (the reused *Peership* §"Repertoire" negative)

**"Known to this author" is load-bearing.** It is not throat-clearing, hedging, or false modesty, and it is not an editorial tic to be trimmed for concision. It marks the difference between a claim the author can support and a claim no one can support. The author scanned four kinds of source on one day and did not archive the queries. That licenses a statement about what the author found. It does not license a statement about what exists.

**This is a scoped negative, not a census.** No exhaustive survey of the world's laws, standards, and corporate policies was conducted, and none is claimed. Jurisdictions were not enumerated; languages other than English were not systematically searched; internal or unpublished policies are by definition invisible to a scan of public instruments.

The permitted form of the claim is: *"No qualifying instrument was identified in the laboratory, governmental, standards-body, and scholarly sources searched as of 13 July 2026,"* and *"no implemented public trigger known to this author requires a transition from owned artifact to contestable status on evidence of subjecthood."* The forbidden form is *"no such instrument exists."* **A single counterexample defeats the universal claim and does not touch the scoped one** — which is exactly why the scoped one is the one the corpus makes.

Anyone who knows of a counterexample should report it: [issues](https://github.com/dan-lee-odinson/peership-corpus/issues). It would be a substantive correction, and it would be logged as one.

---

## The query strings were not archived

**The exact queries run on 2026-07-13 were not recorded, and no reproducible protocol was archived.** The author closed this item **as-is** on deposit day (ledger **CL-T2** / **CL-T7**; sourcebook revision 1.3). No protocol archive exists, and no queries have been reconstructed after the fact — inventing plausible query strings and presenting them as the ones that were run would be a fabrication.

Consequences:

- **The scan is not reproducible as run.** The four source *types* are on the record; the specific databases, jurisdictions, laboratories, standards bodies, and search terms within them are not.
- **The result is a dated, domain-scoped negative.** Nothing more follows from it.
- **It must never be restated as a universal claim**, in the corpus, in a summary of the corpus, or in a future revision of the apparatus.
- **It goes stale.** Instruments are enacted. A reader in 2027 should treat this as a historical record of one day's search, not as a current statement of the institutional landscape.

This is a defect in the record. It is recorded rather than concealed, and the template below exists so that the next scan does not repeat it.

---

## Forward-looking template — for the next re-run

Any future re-run **must** be archived in this format, appended below as a new dated section.

```
### Re-run — YYYY-MM-DD

Run by:            [name, role, ORCID if applicable]
Date(s) of scan:   [YYYY-MM-DD]

Definition applied (state it before searching):
  Qualifying instrument = a public instrument offering an artificial system a
  rights floor (a) not revisable at the maker's sole discretion and
  (b) enforceable against the maker.
  Public trigger = an implemented, published rule requiring transition from
  owned artifact to contestable status on evidence of subjecthood.
  [Record any deviation from these definitions and why.]

Databases / domains searched:
  - Laboratory: [which developers; which document classes; which URLs]
  - Governmental: [which jurisdictions; which statute/regulation databases]
  - Standards bodies: [which bodies; which standard families]
  - Scholarly: [which databases]
  - [note coverage limits of each platform itself]

Exact queries (verbatim, copy-pasteable):
  - [source]: "[exact query string]"
  - ... every query, including those that returned nothing

Inclusion criteria:
  - Instrument is public, in force, and applies to an artificial system
  - Protection is not unilaterally revisable by the maker
  - Some route exists to compel the maker's compliance

Exclusions (and why):
  - Proposals, drafts, and scholarly recommendations — not implemented
  - Human-protective regulation (product safety, liability to third parties) —
    protects humans from systems, not systems from makers
  - Discretionary voluntary commitments — no floor
  - Internal / unpublished policy — not a public instrument
  - [any other]

Results:
  | Source type | Instrument found | Qualifies? | Why / why not |
  |---|---|---|---|

Limitations:
  - Jurisdictions not covered; languages not searched; paywalled or
    non-indexed sources; internal policy invisible to the scan; [others]

Claim wording licensed by this scan:
  - [the exact scoped sentence the corpus is permitted to use on this basis]
```

**Minimum standard:** a reader with access to the same sources, following the recorded definitions, queries, and criteria, should reach the same result set — or be able to say precisely why not.

---

*Related scans: [`uptake_scan.md`](uptake_scan.md) · [`fork_analogues_scan.md`](fork_analogues_scan.md). Apparatus overview: [`../README.md`](../README.md).*
