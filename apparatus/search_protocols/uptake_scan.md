# Uptake Scan — Independent Citation, Criticism, Adoption, Extension

**DATED OPEN INFRASTRUCTURE.** This file records a scan that was actually run, on named dates, over named sources, with a stated result and stated limits. It is **not** a reproducible protocol for the scan as run, and it does not pretend to be one. See [The query strings were not archived](#the-query-strings-were-not-archived) below, which is the most important section in this file.

**Supports:** the uptake baseline in [`peership_sourcebook.md` §5](../peership_sourcebook.md#5-independent-uptake-tracker); ledger **CL-T2**; the *Peership Thesis* §1 statement and the one-pager footer.
**Scan date:** 2026-07-13. **Re-confirmed:** 2026-07-14 (deposit day), no change.
**Run by:** Dan Lee-Odinson (maintainer).

---

## What the scan was looking for

Evidence that someone other than the author has engaged the corpus: external citations, published criticism, symposium or workshop discussion, course or reading-list adoption, researchers using the corpus's definitions, alternative implementations or extensions, and work rejecting Peership after engaging its actual thesis.

The distinction the scan is built to enforce: **a school exists when independent researchers use its definitions, dispute its claims, and pursue its open problems.** Publishing does not create a school. Being read does not create a school. Citing yourself certainly does not.

---

## Result

**None found.** No independent uptake of any kind was identified.

### Results table (2026-07-13; re-confirmed 2026-07-14, no change)

| Uptake type | Result | Evidence relied on |
|---|---|---|
| External citations | None found | Web, PhilPapers, Zenodo, GitHub scan |
| Published criticism | None found | Same |
| Symposium / workshop discussion | None found | Same |
| Course / reading-list adoption | None found | Same |
| Researchers using the corpus's definitions | None found | Same |
| Alternative implementations / extensions | None found | `isonomia-path-a`: 0 forks |
| Rival implementations | None found | Same |
| Work rejecting Peership after engaging its actual thesis | None found | Same |

### Sources actually scanned

| Source | What was checked |
|---|---|
| Open web (general search) | Titles, distinctive phrases, and author name |
| PhilPapers | Author and title presence; citing works |
| Zenodo | Record statistics for the corpus deposits |
| GitHub (`dan-lee-odinson/isonomia-path-a`) | Stars, forks, issues, referring activity |

### Corroborating platform evidence

- The Zenodo records carried **`noindex`**, with **single-digit view counts** and **zero downloads**.
- The `isonomia-path-a` repository had **0 stars** and **0 forks**; its **sole issue was self-authored**.

These figures are the reason the negative is unsurprising rather than informative: the corpus had been public for roughly a week (released 8–13 July 2026) and search engines had not indexed the deposits. A finding of no uptake under those conditions is close to what one would predict on priors. It is recorded because it is the honest baseline against which any later finding is to be measured — **not** because it demonstrates anything about the corpus's merits.

---

## Footprint, not uptake

The corpus has a self-published footprint. It is listed here so that it is never mistaken for reception, and it is **excluded from the results table above by design**.

| Item | Author |
|---|---|
| Five Zenodo deposits (the corpus works) | Lee-Odinson |
| The `isonomia-path-a` GitHub repository | Lee-Odinson |
| A PhilArchive presence | Lee-Odinson |
| A Substack ("The Cosmic Intelligence") variant of *Gods and Slaves* | Lee-Odinson |

Self-citation across the five papers is likewise **corpus architecture, not evidence of independent acceptance**, and does not appear in the tracker.

---

## Unverified convergent-work leads

The 2026-07-13 scan surfaced apparently independent 2025–2026 work on themes overlapping the corpus — for example, republican liberty and non-domination applied to AI — that does **not** reference the corpus. The search tool also returned conflated and unreliable prose alongside these leads, so they are **not treated as real sources** and are **not cited anywhere in the corpus**.

Three rules govern them:

1. **They must be individually verified** against the actual publication before any of them is entered in the bibliography or cited in the corpus.
2. **Convergence, if confirmed, is parallel invention, not uptake.** Independent work that reaches similar ground without knowing of the corpus is evidence that the questions are live. It is not evidence that anyone has taken the corpus up, and it must never be moved into the uptake tracker.
3. **Confirmed leads belong in sourcebook category 3** (precursors and convergent approaches), with the disagreements stated, not annexed into a Peership "tradition."

Confirm-or-discard is an open item, carried in [`../corrections_log.md`](../corrections_log.md).

---

## The query strings were not archived

**The exact queries run on 2026-07-13 were not recorded, and no reproducible protocol was archived.** The author closed this item **as-is** on deposit day (ledger **CL-T2** / **CL-T7**; sourcebook revision 1.3). No protocol archive is claimed to exist, and none has been reconstructed after the fact — reconstructing plausible-looking queries and presenting them as the ones that were run would be a fabrication, and would make the record worse than the gap it filled.

The consequences are exact, and they bind every future use of this finding:

- **The original scan is not reproducible as run.** Another researcher cannot repeat it. They can only run a *new* scan, whose disagreement with this one would be uninformative about which was better executed.
- **The finding is a dated, non-exhaustive negative over the four named sources.** That is all it is.
- **It must never be restated as a universal claim.** The permitted form is: *"No independent uptake was identified in the sources scanned, as of 13 July 2026 (re-confirmed 14 July 2026); the scan was non-exhaustive and its queries were not archived."* The forbidden form is *"there is no independent uptake"* or *"no one has cited the corpus."* The scoping language is permanent and survives every paraphrase, summary, and edit.
- **The finding goes stale immediately.** It is time-sensitive by nature (ledger CL-T2 flags it as such). A reader in 2027 should assume nothing from it.

This limitation is a defect in the record. It is stated here rather than concealed, and the template below exists so that the *next* scan does not repeat it.

---

## Forward-looking template — for the next re-run

Any future re-run **must** be archived in this format, as a new dated section appended below. A scan that cannot be repeated by a stranger is not a scan; it is an assertion.

```
### Re-run — YYYY-MM-DD

Run by:            [name, role, ORCID if applicable]
Date(s) of scan:   [YYYY-MM-DD; note any multi-day window]

Databases / domains searched:
  - [platform] — [what was queried; coverage limits of the platform itself]
  - ...

Exact queries (verbatim, copy-pasteable):
  - [platform]: "[exact query string]"
  - [platform]: "[exact query string]"
  - ... every query, including the ones that returned nothing

Inclusion criteria:
  - [what counts as uptake — e.g. a work not authored by Lee-Odinson that
    cites a corpus DOI, uses a corpus definition, or argues against the thesis]

Exclusions (and why):
  - Self-published footprint (author's own deposits, repo, blog) — footprint, not uptake
  - Self-citation within the corpus — architecture, not uptake
  - Convergent work that does not reference the corpus — parallel invention, not uptake
  - [any other]

Results:
  | Uptake type | Result | Evidence |
  |---|---|---|
  | ... | ... | ... |

Limitations:
  - [platform coverage gaps; indexing lag; noindex status; languages not searched;
    paywalled or non-indexed venues; anything the scan could not have seen]

Claim wording licensed by this scan:
  - [the exact scoped sentence the corpus is permitted to use on the basis of this run]
```

**Minimum standard for a re-run to count as reproducible:** a reader with access to the same platforms, following the recorded queries and criteria, should be able to reach the same result set — or identify precisely why they cannot.

---

*Related scans: [`qualifying_instruments_scan.md`](qualifying_instruments_scan.md) · [`fork_analogues_scan.md`](fork_analogues_scan.md). Apparatus overview: [`../README.md`](../README.md).*
