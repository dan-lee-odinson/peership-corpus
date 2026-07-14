# Corrections Log — Peership Corpus Repository

**Maintainer:** Dan Lee-Odinson (ORCID [0009-0009-9504-0796](https://orcid.org/0009-0009-9504-0796))
**Scope:** corrections made from the **v1.0.0 corpus release (2026-07-14) onward**.
**Licence:** CC BY 4.0

This file is the corrections log **for this repository**. It records what was changed in the apparatus after the corpus was released, who reported it, what was accepted, what was rejected, and why.

It does not duplicate the historical record. The corrections inherited from the v4 compendium — the nineteen entries **C1–C19**, covering the removal of the ontological definition of Peership, the Ord estimate, the Pines & Ash DOI mapping, the reclassification of ISONOMIA as an implementation hypothesis, and the rest — live in [`peership_sourcebook.md` Appendix C](peership_sourcebook.md#appendix-c--corrections-log-from-the-v4-compendium) and remain the authoritative account of that phase. This file begins where that one stops.

---

## Where to propose a correction

**Open an issue on this repository:**

> **<https://github.com/dan-lee-odinson/peership-corpus/issues>**

This is the correct address, and it supersedes the addresses printed elsewhere.

**Recorded supersession.** The archived Zenodo README for the *Peership Thesis* package, and the apparatus files deposited with it — [`peership_sourcebook.md` Appendix D](peership_sourcebook.md#appendix-d--submitting-corrections) in particular — direct correspondents to the ISONOMIA repository (`github.com/dan-lee-odinson/isonomia-path-a`). They do so because **this corpus repository did not exist at deposit** (2026-07-14). The instruction was correct when written and is now out of date. Those deposits are frozen: a Zenodo record cannot be edited, and the archived apparatus files are part of the record. They will therefore continue to point at the wrong tracker, and that cannot be fixed by editing them. This entry is the fix. Correspondence sent to the ISONOMIA tracker will still reach the maintainer; corrections to the *corpus* belong here.

Corrections may also be sent to the maintainer directly (ORCID 0009-0009-9504-0796). An issue is preferred, because it is public and it creates a record that survives the maintainer.

---

## What can and cannot be corrected

**Correctable:** everything in [`apparatus/`](.) — the bibliography, the classification of any source, the annotation of any source, any ledger entry, any scan record, and this log. Also the repository's own documentation.

**Not correctable:** the five corpus papers. They are archived Zenodo deposits and they are frozen. Where a frozen paper contains an error, **the error stays in the paper** and the correction is recorded in the apparatus. (Two such cases are already on the record: the ISONOMIA paper's front matter mislabels `10.5281/zenodo.21338480` a "concept DOI" when it is the v1.0 exact-version DOI — see CL-D3 — and *Constitution, Not Cage*'s front matter describes itself as "third in a series," counting essays only, against the corpus's canonical reading order. Neither artifact was altered.)

---

## Correction workflow

1. **Issue.** A correction is proposed as an issue on this repository. Useful issues name the file, the line or claim ID or citation key, what is wrong, and what the evidence is. Corrections to a claim should cite a source; corrections to metadata should cite the authority (a DOI landing page, a publisher record, a stable URL with an access date).
2. **Triage.** The maintainer assesses the correction and assigns it an ID. Triage determines which artifacts are affected, which claims depend on the item, and whether the change is substantive (it alters what the corpus asserts) or editorial (it does not).
3. **Mirrored update.** An accepted correction is applied to **every affected file in the same change**: `peership_sources.bib`, `peership_sourcebook.md`, `peership_claim_ledger.md`, and any affected scan record under `search_protocols/`. The synchronization rule is described in the [apparatus README](README.md#the-synchronization-rule). A correction applied to one file and not its dependants is a defect, not a correction.
4. **Logged here.** The change is entered in the table below with its date, ID, affected files, reporter, substance, and status. Per-claim revision history is also written into the affected ledger entry's `Revision history` field, which remains the canonical per-claim record.
5. **Reflected in the changelog.** The change is summarized in the repository's [`CHANGELOG.md`](../CHANGELOG.md) under the release that carries it.

A rejected correction is logged too, with a reason. A correction log that records only the corrections that were accepted tells the reader nothing about the maintainer's judgement.

**Status vocabulary.** `ACCEPTED` — applied and mirrored. `REJECTED` — declined; a reason is mandatory. `OPEN` — triaged, accepted in principle, not yet resolved (typically because the underlying evidence has not been obtained). `SUPERSEDED` — the entry has been overtaken by a later correction, which is named.

---

## Corrections since v1.0.0

None. This repository was created at the v1.0.0 release (2026-07-14) and no correction has yet been proposed against it. The table is empty by fact, not by omission.

| Date | ID | Affected files | Reported by | Change | Status |
|---|---|---|---|---|---|
| — | — | — | — | — | — |

---

## Open items carried forward at v1.0.0

These were open in the apparatus at deposit and remain open. They are carried here so that the release does not launder them into "resolved." Each is a live invitation to a correction.

| ID | Item | What would close it |
|---|---|---|
| **CL-F7** | Hinton's extinction-probability statements are not individually pinned. One statement is pinned (EmTech Digital, MIT Technology Review, May 2023); the "10–20%" figure is cited to a topic range ("public statements, 2023–2026"), not to a citable item. Hinton has given varying figures in different venues, so the conflation risk is real. | Individually citable interviews or talks with venue, date, and timestamp, replacing the topic-level citation. |
| **CL-P19** | Sutton, "prepare for, but not fear, the inevitable succession" — pinned at talk level (WAIC Shanghai, September 2023) with **no timestamp**. | An exact timestamp within the recording. |
| **CL-G2** | Crowley, "portions of the human brain" — pinned to *The Initiated Interpretation of Ceremonial Magic* (1904) with **no page**. | A page or section locator in a specified edition. |
| **§5 leads** | The unverified convergent-work leads in [`peership_sourcebook.md` §5](peership_sourcebook.md#5-independent-uptake-tracker): apparently independent 2025–2026 work on overlapping themes (for example, republican liberty and non-domination applied to AI) that does **not** cite the corpus. They are **not** treated as sources and must be **confirmed or discarded individually**. If confirmed, they are **parallel invention, not uptake**, and belong in the sourcebook's category 3 (precursors and convergent approaches), never in the uptake tracker. | Individual verification of each lead against the actual publication. Until then they must not be cited. |
| **Uptake re-run** | The independent-uptake baseline is a **dated negative that decays immediately**. It was true on 2026-07-13 and re-confirmed on 2026-07-14. It is not self-updating, and it has no owner. | A re-run of [`search_protocols/uptake_scan.md`](search_protocols/uptake_scan.md), logged with its own date. Until re-run, the baseline must be cited with its date attached and must never be restated in the present tense. |

---

## Errata in the frozen apparatus (recorded, not edited)

Two defects exist in the deposited apparatus files. They are **recorded here and not
corrected in place**, because `peership_sourcebook.md`, `peership_claim_ledger.md` and
`peership_sources.bib` as committed are byte-identical to the copies inside the Zenodo
deposit (verified — see [`../CHECKSUMS.sha256`](../CHECKSUMS.sha256)). Editing them here
would silently fork the apparatus from the archived record, which is precisely the failure
mode the corpus's version discipline exists to prevent. Both should be fixed in the **next
apparatus revision**, which will then be re-deposited and re-checksummed.

| ID | File | Defect | Disposition |
|---|---|---|---|
| **E1** | `peership_claim_ledger.md` (scope statement, §"Scope of this version") | The coverage sentence says the ledger logs claims "across all **four** corpus papers." There are **five**. §6 (`CL-T#`, *The Peership Thesis*) is listed three lines below the same sentence, so the statement is internally contradicted by its own section list. A leftover from the v1.0 ledger, which predated paper V. | **OPEN.** Cosmetic, but it sits in the artifact whose entire purpose is internal consistency. Fix at the next apparatus revision: "across all five corpus papers." |
| **E2** | `peership_claim_ledger.md`, and repeated in the sourcebook and in *The Peership Thesis* reference list | The ledger's coverage is described as "**~71** logged claims." The file contains **70** unique claim IDs (`CL-C` 16, `CL-P` 20, `CL-F` 9, `CL-G` 9, `CL-T` 7, `CL-I` 6, `CL-D` 3). The tilde makes the figure defensible rather than false, but a corpus that pins DOIs to the final digit should be able to count its own claims. | **OPEN.** Documentation of this repository uses the exact figure, **70**, and points here. The frozen papers and apparatus retain "~71" and are not altered. Reconcile at the next apparatus revision. |

Neither erratum affects any claim's substance, source, pinpoint, or evidentiary strength.

---

## Items closed at deposit (2026-07-14)

Recorded for completeness. These closed before this repository existed and are not "corrections since v1.0.0"; they are the state the repository inherited.

| ID | Item | Disposition |
|---|---|---|
| **CL-D3** | The ISONOMIA preprint DOI relation: the paper's front matter labels `10.5281/zenodo.21338480` a "concept DOI." | **RESOLVED.** `…21338480` is the **v1.0 exact-version DOI**; `…21338479` is the **concept (all-versions) DOI**. An ordinary version-vs-inclusive pair, not a dispute. Recorded in the `.bib`, sourcebook §3.3, and ledger CL-D3. The frozen paper was not altered. (The separate `isonomia-path-a` repository's own version manifest still carries the old label; correcting that repository is out of scope here.) |
| **CL-T2** | Deposit-day rerun of the independent-uptake scan. | **CLOSED — no change** from the 2026-07-13 baseline. |
| **CL-T2 / CL-T7** | Archiving of a reproducible search protocol for the negative scans. | **CLOSED AS-IS** by author decision. No reproducible protocol was archived and none is claimed. The dated, non-exhaustive scan summary stands as the permanent record, and the claims it supports keep their scoping language permanently. See [`search_protocols/`](search_protocols/), which records this limitation explicitly rather than reconstructing queries that were never run. |
| — | The four flagged citation spot-checks outstanding on the pre-publish checklist. | **CLOSED — author-confirmed.** |

---

*This log is versioned with the repository and is itself correctable. If an entry here is wrong, open an issue.*
