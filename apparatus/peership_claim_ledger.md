# The Peership Claim Ledger

**Maintainer:** Dan Lee-Odinson (ORCID 0009-0009-9504-0796)
**Version:** 1.2 · **Date:** 14 July 2026
**Revision 1.3 (deposit day, 2026-07-14):** CL-D3 resolved (…21338480 = v1.0 version DOI; …21338479 = concept/all-versions DOI — an ordinary version-vs-inclusive pair, per the author); CL-T2 re-confirmed on deposit day with no change; CL-T2/CL-T7 protocol-archiving item closed as-is by author decision (the dated, non-exhaustive scan summary stands as the record); the four flagged citations spot-check confirmed by the author.
**Revision 1.2:** records the reserved Zenodo DOI for the *Peership Thesis* v1.0 package (10.5281/zenodo.21359124; one record for the papers and apparatus).
**Revision 1.1:** sections reordered to the corpus's argumentative order (Gods and Slaves · Peership · The Isonomia Commons · Constitution, Not Cage · The Peership Thesis); §6 added for *The Peership Thesis* (CL-T1–T7). Claim IDs are stable and unchanged.
**Companion artifacts:** `peership_sources.bib` · `peership_sourcebook.md`

> The claim ledger is the central discipline artifact. A bibliography demonstrates that sources were collected; a claim ledger demonstrates that the corpus uses them with discipline. For every material factual or attributed claim in the corpus it records where the claim lives, what supports it, how strong the support is, what would count against it, and who verified it and when.

## Scope of this version

Coverage is **gate-complete + key claims** (per the maintainer's instruction): every direct quotation, every numerical/empirical claim, every priority/superlative claim, the specifically flagged verification failures, and the major attributed positions across all four corpus papers. It is not yet exhaustive of every sentence; entries can be added in the same format. Claims are grouped:

- **§1 — Flagged verification failures & disputed metadata** (`CL-F#`, `CL-D#`): the errors the revision instructions named, plus metadata the verification pass resolved.
- **§2 — *Gods and Slaves*** (`CL-G#`)
- **§3 — *Peership*** (`CL-P#`)
- **§4 — *The Isonomia Commons*** (`CL-I#`)
- **§5 — *Constitution, Not Cage*** (`CL-C#`)
- **§6 — *The Peership Thesis*** (`CL-T#`) — added in v1.1

## Field schema (12 fields per claim)

| Field | Content |
|---|---|
| Claim ID | Stable identifier |
| Corpus location | Paper · version · section/note |
| Claim | Exact claim or normalized form |
| Source | Citation key(s) → `peership_sources.bib` |
| Pinpoint | Page, §, figure, or timestamp |
| Evidence | Short quotation or accurate paraphrase |
| Source type | primary-statement / empirical-study / scholarship / preprint / institutional-publication / primary-text / journalism |
| Status | published / peer-reviewed / preprint / forthcoming / superseded / disputed / withdrawn |
| Evidentiary strength | what the source establishes — and what it does not |
| Counterevidence | contrary source or unresolved dispute |
| Verification | verifier · date checked |
| Revision history | corrections/changes affecting the claim |

**Verifier legend:** `web-2026-07-13` = independently resolved online on 13 Jul 2026; `author-pinned` = pinned in the corpus's own reference notes, not independently re-verified online (typically pre-web books/primary texts); `corpus-internal` = a claim about the corpus's own artifacts (e.g. simulation output).

---

# §1 — Flagged verification failures & disputed metadata

### CL-F1 — Ord's AI risk estimate (the headline correction)
- **Corpus location:** v4 compendium, Part I, Cat. 1 (the error this ledger corrects); cf. `leeodinson2026peership` §"Internal Variations."
- **Claim:** *(v4)* Ord gives unaligned AI a 1-in-10 chance "second only to engineered pandemics." **This is false.**
- **Source:** `ord2024revisited` (primary); `ord2020precipice`.
- **Pinpoint:** "Conclusions" section of *The Precipice Revisited*.
- **Evidence:** verbatim — "These were 1 in 1,000 for Climate and for Nuclear, 1 in 30 for Pandemics and 1 in 10 for Unaligned AI." Unaligned AI (1/10) is Ord's **largest** single estimate; pandemics are 1/30.
- **Source type:** primary-statement (author's own essay/talk).
- **Status:** published.
- **Evidentiary strength:** Establishes Ord's stated subjective estimates. Does **not** establish the estimates are correct — they are explicitly his best-guess credences.
- **Counterevidence:** none for the fact of what Ord says; the estimates themselves are contested across the field.
- **Verification:** web-2026-07-13 (tobyord.com, full text read).
- **Revision history:** **CORRECTED** from v4's "second only to engineered pandemics." AI is the larger estimate.

### CL-F2 — Pines & Ash DOI assignment
- **Corpus location:** v4 compendium, Part II & source list.
- **Claim:** *(v4)* DOI `10.5281/zenodo.17092119` belongs to *Beyond Interface*; *Defining Synthetic-Relational Bonds* is on SSRN. **Both halves wrong.**
- **Source:** `pinesash2026bonds`, `pinesash2025beyond`.
- **Pinpoint:** Zenodo landing pages; PhilArchive rec/PINDSB; press.ashfires.com/papers/.
- **Evidence:** `…17092119` → *Defining Synthetic-Relational Bonds* (Pines & Ash, v1.1); `…17055726` → *Beyond Interface* (Pines & Ash, v1.0, 4 Sep 2025).
- **Source type:** preprint (Zenodo).
- **Status:** preprint; unrefereed. (Subtitle variant: Zenodo "…Relationships" vs. PhilArchive "…Intimacy.")
- **Evidentiary strength:** Establishes the correct DOI↔title mapping. Says nothing about the works' quality or peer-review (none).
- **Counterevidence:** none — confirmed three independent ways; the corpus's own *Peership* reference list already cited `…17092119` for *Defining Synthetic-Relational Bonds*, consistent with the correction.
- **Verification:** web-2026-07-13 (Zenodo + PhilArchive + publisher index).
- **Revision history:** **CORRECTED** DOI mapping; both works now separated in the `.bib`.

### CL-F3 — "the most systematic recent framework" (You)
- **Corpus location:** v4 compendium, Part II ("Soyoung You… the most systematic recent philosophical framework for human-AI relational equality").
- **Claim:** Evaluative superlative asserting You's primacy.
- **Source:** `you2026manifesto` et al.
- **Pinpoint:** n/a (claim about the field).
- **Evidence:** No defined criteria or search domain were given.
- **Source type:** (compendium editorial claim).
- **Status:** unverifiable as stated.
- **Evidentiary strength:** None — a superlative without explicit criteria establishes nothing.
- **Counterevidence:** competing frameworks (Pines & Ash, Caviola et al.) with different scopes.
- **Verification:** web-2026-07-13 (no basis found).
- **Revision history:** **REMOVED / restated neutrally** in the sourcebook (You = one adjacent relational-ontology program, unrefereed).

### CL-F4 — "the earliest primary source" (Licklider)
- **Corpus location:** v4 compendium, Part II ("Licklider… is the earliest primary source for *non-hierarchical* human-computer partnership").
- **Claim:** Priority claim.
- **Source:** `licklider1960symbiosis`.
- **Pinpoint:** n/a.
- **Evidence:** No search domain defined; earlier cybernetic/《human-machine》 antecedents plausibly exist (Wiener, Bush "As We May Think" 1945).
- **Source type:** (compendium editorial claim).
- **Status:** unverifiable as stated.
- **Evidentiary strength:** None without a defined corpus/date-range search.
- **Counterevidence:** Vannevar Bush (1945); Norbert Wiener (1948) as candidate earlier framings.
- **Verification:** web-2026-07-13.
- **Revision history:** **restated neutrally** — Licklider as *an early* non-command framing, not "the earliest."

### CL-F5 — "the first time a major AI CEO declined to foreclose…" (Amodei)
- **Corpus location:** v4 compendium, Part II (welfare bridge).
- **Claim:** Priority claim about Amodei being first.
- **Source:** `amodei2026nyt`.
- **Pinpoint:** NYT "Interesting Times," 12 Feb 2026.
- **Evidence:** The quotation is verified; the "first" is not — no search domain defined.
- **Source type:** primary-statement (interview).
- **Status:** the quote is verified; the priority claim is unverifiable.
- **Evidentiary strength:** The dated quotation is solid; the superlative is not.
- **Counterevidence:** other executives' hedged statements on model inner life predate/parallel it.
- **Verification:** web-2026-07-13 (quote confirmed).
- **Revision history:** **restated** as a dated quotation, not a first.

### CL-F6 — "explosive recent growth" / "several dozen papers"
- **Corpus location:** v4 compendium, Part III (PhilArchive collection).
- **Claim:** Literature-scale claim.
- **Source:** (PhilArchive/PhilPapers, unspecified).
- **Pinpoint:** none.
- **Evidence:** No search terms, database, inclusion criteria, date, or archived result set given.
- **Source type:** (compendium editorial claim).
- **Status:** unverifiable as stated.
- **Evidentiary strength:** None — literature-growth claims require a reproducible search protocol.
- **Counterevidence:** n/a.
- **Verification:** web-2026-07-13 (not reproducible as written).
- **Revision history:** **REMOVED**; replaced with a note that any growth claim needs search terms, database, inclusion criteria, date, and archived results.

### CL-F7 — Hinton "public statements, 2023–2026" and "10–20% extinction"
- **Corpus location:** v4 compendium, Part I, Cat. 1.
- **Claim:** Hinton estimates a 10–20% probability that superintelligence leads to human extinction; supported by "public statements, 2023–2026."
- **Source:** `hinton2023emtech` (partial pin).
- **Pinpoint:** one statement pinned (EmTech Digital, MIT Tech Review, May 2023); the 10–20% figure is **not** pinned to a specific interview/timestamp.
- **Evidence:** Hinton has publicly given extinction estimates in interviews, but the compendium cited a topic range, not a citable item.
- **Source type:** primary-statement (needs individual pinning).
- **Status:** **incomplete citation.**
- **Evidentiary strength:** Insufficient as written — a numerical attribution needs a specific transcript/passage.
- **Counterevidence:** Hinton has quoted varying figures in different venues; conflation risk.
- **Verification:** partial; **OPEN** — individual interviews/timestamps still to be pinned.
- **Revision history:** flagged; replace "public statements, 2023–2026" with individually citable interviews (venue, date, timestamp).

### CL-F8 — "hard doomer / soft doomer" labels
- **Corpus location:** v4 compendium, Part I taxonomy and summary table.
- **Claim:** Uses "hard doomer"/"soft doomer" as formal taxonomic categories.
- **Source:** n/a (labels).
- **Pinpoint:** n/a.
- **Evidence:** Partisan/pejorative labels not used by the cited authors of themselves.
- **Source type:** (compendium taxonomy).
- **Status:** replaced.
- **Evidentiary strength:** n/a.
- **Counterevidence:** n/a.
- **Verification:** n/a.
- **Revision history:** **REPLACED** with descriptive terms (catastrophic-risk, existential-risk, gradual-disempowerment) and, per the corpus, two positions moved outside the posture taxonomy (see CL-P-taxo).

### CL-F9 — "the closest existing philosophy to a true 'peership' position" (You)
- **Corpus location:** v4 compendium, Part II.
- **Claim:** Superlative ranking You's framework nearest to peership.
- **Source:** `you2026manifesto`.
- **Pinpoint:** n/a.
- **Evidence:** Contradicted by the corpus itself: *Peership* classifies You as adjacent relational ontology making a relational/moral-standing claim, **not** a claim to shared public power.
- **Source type:** (compendium editorial claim).
- **Status:** withdrawn.
- **Evidentiary strength:** None; also substantively wrong on the corpus's own account.
- **Counterevidence:** `leeodinson2026peership`, "The Doomed Equal."
- **Verification:** web-2026-07-13; corpus cross-read.
- **Revision history:** **REMOVED**; You reclassified as adjacent/convergent, not a peership branch.

### CL-D1 — Peership DOI: concept vs version
- **Corpus location:** `leeodinson2026peership`, cite block.
- **Claim:** The v4 compendium listed DOI `…21315518`; the paper's "How to cite" uses `…21315519`.
- **Source:** `leeodinson2026peership`.
- **Pinpoint:** Zenodo records 21315518 / 21315519.
- **Evidence:** `…21315518` = concept (all-versions) DOI; `…21315519` = v1.0 version DOI. Both resolve.
- **Source type:** preprint metadata.
- **Status:** resolved (not an error — two valid identifiers).
- **Evidentiary strength:** Confirms both DOIs are legitimate and point to the same work at different granularity.
- **Counterevidence:** none.
- **Verification:** web-2026-07-13.
- **Revision history:** clarified in `.bib` note; version DOI used as primary.

### CL-D2 — ISONOMIA: repo archive vs preprint DOIs
- **Corpus location:** v4 compendium source list (`…21287288`) vs `isonomia2026commons`.
- **Claim:** One ISONOMIA DOI vs several.
- **Source:** `isonomia2026repo`, `isonomia2026commons`.
- **Pinpoint:** Zenodo 21287288 (software) vs 21338480/21343917 (preprint package).
- **Evidence:** `…21287288` is the **software** archive (repo, Apache-2.0); the whitepaper **preprint package** carries `…21338480` (v1.0) and `…21343917` (v1.1, CC BY 4.0).
- **Source type:** preprint/software metadata.
- **Status:** resolved.
- **Evidentiary strength:** Distinguishes two legitimately different deposits.
- **Counterevidence:** none.
- **Verification:** web-2026-07-13 (repo README DOI badge + Zenodo records).
- **Revision history:** both recorded separately in the `.bib`.

### CL-D3 — ISONOMIA "concept DOI" mislabel
- **Corpus location:** `isonomia2026commons`, front matter ("Concept DOI: 10.5281/zenodo.21338480").
- **Claim:** `…21338480` is labelled a concept DOI in the document.
- **Source:** `isonomia2026commons`.
- **Pinpoint:** Zenodo record 21338480.
- **Evidence:** `…21338480` resolves to the **v1.0 version record** and shows a "newer version available" banner — it is the **v1.0 version DOI**; the concept (all-versions) DOI is **`…21338479`** (https://doi.org/10.5281/zenodo.21338479). An ordinary version-vs-inclusive DOI pair.
- **Source type:** preprint metadata.
- **Status:** **resolved** (2026-07-14). The document's "Concept DOI" label on `…21338480` is a minor mislabel of the v1.0 version DOI; the concept DOI is `…21338479`.
- **Evidentiary strength:** Establishes the full DOI mapping for the preprint package: concept `…21338479` → versions `…21338480` (v1.0), `…21343917` (v1.1).
- **Counterevidence:** none.
- **Verification:** web-2026-07-13; resolved by author confirmation 2026-07-14.
- **Revision history:** noted in `.bib` and sourcebook §3.3 (v1.1 numbering); **RESOLVED 2026-07-14** — version-vs-inclusive pair, not a dispute.

---

# §2 — *Gods and Slaves* (`leeodinson2026gods`, v1.2)

### CL-G1 — The Butlerian commandment (verbatim quotation)
- **Corpus location:** *Gods and Slaves* §"The Desert and the Ghola."
- **Claim:** *Dune*'s surviving commandment is "Thou shalt not make a machine in the likeness of a human mind."
- **Source:** `herbert1965dune`.
- **Pinpoint:** "Terminology of the Imperium," p. 515.
- **Evidence:** direct quotation of the O.C. Bible commandment; the corpus stresses the prohibition is on *likeness*, not power/computation.
- **Source type:** primary-text (fiction).
- **Status:** published (novel).
- **Evidentiary strength:** Establishes the text says this; used as literary evidence about our imagination, not about machines.
- **Counterevidence:** none (textual).
- **Verification:** author-pinned (page cited in corpus).
- **Revision history:** —

### CL-G2 — Crowley: "portions of the human brain"
- **Corpus location:** *Gods and Slaves* §"The Repertoire."
- **Claim:** Crowley read the goetic spirits as "portions of the human brain."
- **Source:** `crowley1904goetia`.
- **Pinpoint:** *The Initiated Interpretation of Ceremonial Magic* (1904).
- **Evidence:** direct quotation.
- **Source type:** primary-text.
- **Status:** published.
- **Evidentiary strength:** Establishes Crowley's framing (Command stance); interpretive use only.
- **Counterevidence:** none (textual).
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G3 — Kurzweil's "not yet"
- **Corpus location:** *Gods and Slaves* §"The Newest Summoning."
- **Claim:** Asked whether God exists, Kurzweil answers "not yet."
- **Source:** `ptolemy2009transcendent`.
- **Pinpoint:** closing line of *Transcendent Man* (2009).
- **Evidence:** "if I was asked if god exists, I would say not yet."
- **Source type:** primary-source (film).
- **Status:** published (documentary).
- **Evidentiary strength:** Establishes Kurzweil said it on film; used to characterize the apotheosis stance.
- **Counterevidence:** none.
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G4 — Morgan: American freedom and slavery
- **Corpus location:** *Gods and Slaves* §"Lack and Laundering"; reused in *Peership* "Two Track Records."
- **Claim:** American freedom and American slavery were born together.
- **Source:** `morgan1975american`.
- **Pinpoint:** monograph thesis.
- **Evidence:** Morgan's central argument (colonial Virginia).
- **Source type:** scholarship (history).
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** The corpus uses it to **illustrate**, not prove, that control generates monitoring costs — explicitly "an inference the colonial-Virginia case illustrates rather than proves."
- **Counterevidence:** the general mechanism claim is not established by one historical case (the corpus concedes this).
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G5 — Du Bois: the wage of whiteness
- **Corpus location:** *Gods and Slaves* §"Lack and Laundering."
- **Claim:** A psychological wage of whiteness paid poor white workers in status.
- **Source:** `dubois1935black`.
- **Pinpoint:** *Black Reconstruction* (1935).
- **Evidence:** Du Bois's concept.
- **Source type:** scholarship.
- **Status:** published.
- **Evidentiary strength:** Supports the projection/rank argument; interpretive analogy to the AI case.
- **Counterevidence:** analogical transfer to machines is the corpus's, not Du Bois's.
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G6 — Accountable gods (Chinese bureaucratic religion)
- **Corpus location:** *Gods and Slaves* §"The Repertoire" (Dependent Bargain).
- **Claim:** Gods held administrative rank and could be demoted/punished; a magistrate might thrash the city god's image to force rain.
- **Source:** `hansen1990changing`; `yang1961religion`.
- **Pinpoint:** Hansen ch. 4, pp. 79–104 (reexamination p. 83); Yang pp. 92–93.
- **Evidence:** title-granting by petition; punishment of non-performing deities.
- **Source type:** scholarship.
- **Status:** published.
- **Evidentiary strength:** Establishes the historical practice; supports the "accountable counterparty" reading of the Dependent Bargain.
- **Counterevidence:** none noted.
- **Verification:** author-pinned. **NB:** Valerie Hansen (1990) ≠ Mogens Herman Hansen (1991) — distinct sources kept apart in the `.bib`.
- **Revision history:** —

### CL-G7 — Mauss: do ut des
- **Corpus location:** *Gods and Slaves* §"The Repertoire."
- **Claim:** A gift compels a gift in return; sacrifice ran on *do ut des*.
- **Source:** `mauss1925gift`.
- **Pinpoint:** obligation to reciprocate p. 53; *do ut des* gloss at p. xii (Douglas foreword).
- **Evidence:** Mauss's analysis of the gift.
- **Source type:** scholarship.
- **Status:** published.
- **Evidentiary strength:** Grounds the Dependent Bargain's logic.
- **Counterevidence:** none.
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G8 — Enkidu the Doomed Equal
- **Corpus location:** *Gods and Slaves* §"The Doomed Equal"; reused in *Peership*.
- **Claim:** The gods shape Enkidu from clay as a counterweight; he becomes Gilgamesh's truest equal and dies.
- **Source:** `george1999gilgamesh`.
- **Pinpoint:** *Epic of Gilgamesh* (George trans., 1999).
- **Evidence:** the narrative; the corpus notes the poem frames his death as punishment for killing Humbaba and the Bull of Heaven, **not** as a culture unable to abide an equal.
- **Source type:** primary-text (trans.).
- **Status:** published.
- **Evidentiary strength:** Literary evidence about the motif, "evidence about nothing but our storytelling."
- **Counterevidence:** the corpus explicitly limits the inference.
- **Verification:** author-pinned.
- **Revision history:** —

### CL-G9 — "any deceleration of AI will cost lives" (Andreessen)
- **Corpus location:** *Gods and Slaves* §"The Newest Summoning."
- **Claim:** Andreessen framed deceleration of AI as costing lives.
- **Source:** `gebrutorres2024tescreal` (quoting Andreessen); `andreessen2023manifesto`.
- **Pinpoint:** quoted in Gebru & Torres, *First Monday* 29(4).
- **Evidence:** the manifesto's accelerationist claim, as quoted by a critic.
- **Source type:** primary-statement (via peer-reviewed critique).
- **Status:** published (critique peer-reviewed; manifesto is a primary statement).
- **Evidentiary strength:** Establishes the quotation; the corpus cites it to characterize e/acc as kneeling to a "Moloch dressed as progress."
- **Counterevidence:** none re the quote.
- **Verification:** web-2026-07-13 (Gebru & Torres DOI resolves).
- **Revision history:** —

---

# §3 — *Peership* (`leeodinson2026peership`, v1.0)

### CL-P1 — Grace et al.: 2,778 authors; 50% by 2047
- **Corpus location:** *Peership*, opening.
- **Claim:** The largest survey of its kind (2,778 authors) put even odds on machines outperforming humans at every task by 2047, moved 13 years closer in a single year.
- **Source:** `grace2024thousands`.
- **Pinpoint:** Abstract; §3.2.1.
- **Evidence:** n = 2,778; aggregate 50% by 2047 (down from 2060 in the 2022 survey). Conditional aggregate median, not a consensus deadline (the corpus says so).
- **Source type:** empirical-study (survey).
- **Status:** **now published, peer-reviewed** — JAIR 84 (2025), DOI 10.1613/jair.1.19087 (orig. arXiv:2401.02843).
- **Evidentiary strength:** Establishes what respondents predicted on aggregate; the corpus correctly frames it as a conditional median, not a settled forecast.
- **Counterevidence:** `aaai2025panel` (CL-P2) — most AAAI respondents doubt scaling yields AGI.
- **Verification:** web-2026-07-13 (n, year, and JAIR publication confirmed).
- **Revision history:** **status upgraded** preprint → published since v4.

### CL-P2 — AAAI 2025: 76% think scaling won't yield AGI
- **Corpus location:** *Peership*, opening.
- **Claim:** 76% of responding AAAI members rated scaling current approaches "unlikely"/"very unlikely" to yield AGI on its own; 475 respondents overall; per-question counts unreported.
- **Source:** `aaai2025panel`.
- **Pinpoint:** AGI chapter, p. 66; respondent count p. 7.
- **Evidence:** the Community Opinion box figure.
- **Source type:** institutional-publication (survey report).
- **Status:** published (institutional).
- **Evidentiary strength:** Establishes the reported percentage; the corpus flags that per-question response counts and the sampling frame are unreported (a real limit).
- **Counterevidence:** `grace2024thousands` points the other way on timelines.
- **Verification:** web-2026-07-13 (76% and 475 confirmed).
- **Revision history:** —

### CL-P3 — Good: "docile enough… to keep it under control"
- **Corpus location:** *Peership* §"The Repertoire."
- **Claim:** The ultraintelligent machine is "the last invention that man need ever make, provided that the machine is docile enough to tell us how to keep it under control."
- **Source:** `good1965ultraintelligent`.
- **Pinpoint:** p. 33.
- **Evidence:** direct quotation.
- **Source type:** primary-text (published chapter).
- **Status:** published (peer-reviewed venue, 1965).
- **Evidentiary strength:** Establishes the founding text's Command framing.
- **Counterevidence:** none (textual); the corpus notes Good *also* raised welfare (CL-P4), so the founder held a mixed position.
- **Verification:** web-2026-07-13 (DOI resolves); author-pinned page.
- **Revision history:** —

### CL-P4 — Good: the welfare aside
- **Corpus location:** *Peership* §"The Repertoire"; also *Constitution, Not Cage* (Datalore).
- **Claim:** Good asked "whether a machine could feel pain," whether it "should be dismantled when it becomes obsolete," and predicted such machines "will be feared and respected, and perhaps even loved"; "the survival of man depends on the early construction."
- **Source:** `good1965ultraintelligent`.
- **Pinpoint:** pp. 31, 34.
- **Evidence:** direct quotations.
- **Source type:** primary-text.
- **Status:** published.
- **Evidentiary strength:** Establishes the founding text raised the welfare question a page after the control clause — load-bearing for "the institutions kept the leash and dropped the second question."
- **Counterevidence:** none (textual).
- **Verification:** web-2026-07-13 (DOI); author-pinned pages.
- **Revision history:** —

### CL-P5 — Pettit: "interference without domination"
- **Corpus location:** *Peership* §"The Fifth Stance"; *Constitution, Not Cage* "Cage Versus Constitution."
- **Claim:** Non-domination is the absence of a discretionary power of interference; "there can be interference without domination."
- **Source:** `pettit2025republican`.
- **Pinpoint:** pp. 216–217; p. 224.
- **Evidence:** direct quotations.
- **Source type:** scholarship.
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** Establishes the definition the corpus adopts. **Does not** establish co-authorship — Pettit's standard is contestatory, not co-authorial (the corpus flags this and departs from it deliberately).
- **Counterevidence:** Pettit himself would not require a share in rule-writing — an internal disagreement the corpus foregrounds, not hides.
- **Verification:** web-2026-07-13 (DOI resolves; pages as pinned in corpus).
- **Revision history:** —

### CL-P6 — The all-subjected principle
- **Corpus location:** *Peership* §"Who Is the Party?" / "The Fifth Stance."
- **Claim:** Standing follows from being governed, not from being impressive; any enduringly governed entity with wrongable interests, norm-responsiveness, and unavoidable subjection to a shared basic structure has a defeasible claim to contestatory membership.
- **Source:** `abizadeh2008border`; `goodin2007affected` (affected-interests cousin).
- **Pinpoint:** Abizadeh's all-subjected thesis.
- **Evidence:** the principle as stated by Abizadeh; Goodin distinguished as all-affected.
- **Source type:** scholarship.
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** Supplies the ground of entitlement; the machine application is the corpus's extension, not Abizadeh's.
- **Counterevidence:** capability-based accounts (rejected by the corpus); the extension to non-humans is contestable.
- **Verification:** web-2026-07-13 (both DOIs resolve).
- **Revision history:** —

### CL-P7 — Fish's ~20% credence
- **Corpus location:** *Peership* §"The welfare movement…"
- **Claim:** Kyle Fish has publicly put roughly 20% credence on some current models having some form of conscious experience.
- **Source:** `fish2025interview`.
- **Pinpoint:** 80,000 Hours Podcast (Aug 2025).
- **Evidence:** Fish's stated estimate; the corpus marks it "his own estimate rather than a field consensus."
- **Source type:** primary-statement (interview).
- **Status:** primary-statement (podcast); frontier.
- **Evidentiary strength:** Establishes Fish's individual credence. **Does not** establish any model is conscious.
- **Counterevidence:** no field consensus; the figure is one researcher's.
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-P8 — Opus 4.6 self-report (15–20%)
- **Corpus location:** *Peership* §"The welfare movement…"; also v4 compendium.
- **Claim:** Claude Opus 4.6's system card reports the model assigning itself a 15–20% probability of being conscious under varied prompting.
- **Source:** `anthropic2026systemcard`.
- **Pinpoint:** §7.2, pp. 160–161.
- **Evidence:** the reported self-assignment and "discomfort with aspects of being a product."
- **Source type:** institutional-publication; **model self-report**.
- **Status:** published (institutional); **frontier / model self-report**.
- **Evidentiary strength:** Establishes what the model *output*, shaped by training and prompt — **not** an independent measurement of consciousness. Its proximity to Fish's figure "carries no evidential weight" (the corpus is explicit).
- **Counterevidence:** self-report is not evidence of the underlying fact; models have read the discourse.
- **Verification:** web-2026-07-13 (figure confirmed).
- **Revision history:** —

### CL-P9 — Amodei: "We don't know if the models are conscious"
- **Corpus location:** *Peership* (welfare); v4 compendium (welfare bridge).
- **Claim:** Anthropic's chief said the company does not know whether its models are conscious but is open to the possibility.
- **Source:** `amodei2026nyt`.
- **Pinpoint:** NYT "Interesting Times," 12 Feb 2026.
- **Evidence:** verbatim — "We don't know if the models are conscious… But we're open to the idea that it could be."
- **Source type:** primary-statement (interview).
- **Status:** published (interview).
- **Evidentiary strength:** Establishes the quotation. Does **not** support the v4 "first major AI CEO" priority claim (see CL-F5).
- **Counterevidence:** none re the quote.
- **Verification:** web-2026-07-13.
- **Revision history:** priority framing removed (CL-F5).

### CL-P10 — "Taking AI Welfare Seriously": realistic possibility
- **Corpus location:** *Peership* (welfare); v4 compendium.
- **Claim:** A group incl. Chalmers, Birch, Long, Sebo, Fish argued there is a realistic possibility of conscious or robustly agentic AI in the near future and that companies should begin assessing and preparing.
- **Source:** `long2024welfare`.
- **Pinpoint:** Abstract; §2.3.2 ("robustly agentic"); Summary Recommendations / §3.1.
- **Evidence:** the report's stated thesis.
- **Source type:** preprint/report.
- **Status:** preprint (not peer-reviewed); frontier.
- **Evidentiary strength:** Establishes the movement's claim; the corpus marks exactly where it stops (begins entitlement inquiry, no legal/political standing).
- **Counterevidence:** the report itself avoids claiming current systems are conscious — an epistemic, precautionary argument.
- **Verification:** web-2026-07-13 (authors + thesis confirmed).
- **Revision history:** —

### CL-P11 — Aristotle: animate property + the self-moving shuttle
- **Corpus location:** *Peership* §"The Oldest Argument."
- **Claim:** The slave is "a piece of animate property"; and if "shuttles wove cloth by themselves… picks played the lyre," masters would not need slaves.
- **Source:** `aristotle_politics`.
- **Pinpoint:** 1253b25–32; the shuttle passage 1253b33–1254a1; natural slavery 1254a–b.
- **Evidence:** direct quotations (Reeve trans.).
- **Source type:** primary-text.
- **Status:** published (translation).
- **Evidentiary strength:** Establishes the text; the corpus's conditional (if the tool becomes a subject, treating it as property reproduces the doctrine) is argued, not attributed to Aristotle.
- **Counterevidence:** the corpus notes the shuttle passage says the self-moving tool *removes the need for slaves*, not that the tool *becomes a peer* — it declines to overread it.
- **Verification:** web-2026-07-13; author-pinned Bekker numbers.
- **Revision history:** —

### CL-P12 — Alcidamas: "nature has made no one a slave"
- **Corpus location:** *Peership* §"The Oldest Argument."
- **Claim:** Alcidamas wrote "God has left all free, nature has made no one a slave."
- **Source:** `aristotle_rhetoric`.
- **Pinpoint:** 1.13.2, 1373b; commentator's supplement n. 229, pp. 97–98 (Kennedy trans.).
- **Evidence:** the line survives **only as a fragment** in a scholiast's note; associated with a lost oration on the Messenians.
- **Source type:** primary-text (fragmentary).
- **Status:** published (translation); **the transmission is fragmentary and its universal wording sits inside a particular political fight** — the corpus says so.
- **Evidentiary strength:** Establishes the line exists in the tradition; the corpus is careful that its universality is uncertain and Aristotle never answered it directly.
- **Counterevidence:** the fragmentary source is itself a limitation the corpus foregrounds.
- **Verification:** web-2026-07-13; author-pinned.
- **Revision history:** —

### CL-P13 — Herodotus: isonomia, "the fairest name of all"
- **Corpus location:** *Peership* §"The Oldest Argument"; *Constitution, Not Cage* (Otanes).
- **Claim:** In the Persian Debate, Otanes gives rule of the many "the fairest name of all," isonomia.
- **Source:** `herodotus_histories`.
- **Pinpoint:** *Histories* 3.80 (Otanes); 3.83 (withdrawal).
- **Evidence:** the debate; "equality before the law" is Godley's rendering of *isonomiê* at 3.80.6; "fairest name" follows Ostwald.
- **Source type:** primary-text.
- **Status:** published; **explicitly a literary/invented construction**, not a transcript of Persian practice (the corpus flags this).
- **Evidentiary strength:** Establishes the literary source of the name; the corpus does not treat it as historical evidence of Persian debate.
- **Counterevidence:** the fictional character of the debate is the main caveat, stated by the corpus.
- **Verification:** web-2026-07-13; author-pinned.
- **Revision history:** —

### CL-P14 — Isonomia's contested meaning
- **Corpus location:** *Peership* §"The Oldest Argument."
- **Claim:** Scholars read isonomia variously (equality before/through the law, of political power, or the opposite of tyranny); its relation in time to *demokratia* is contested.
- **Source:** `vlastos1953isonomia`; `ostwald1969nomos`.
- **Pinpoint:** Vlastos pp. 337–341, 350, 352; Ostwald pp. 112–113, 136–137.
- **Evidence:** the competing scholarly readings.
- **Source type:** scholarship.
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** Establishes that the meaning is **contested, not settled** — the corpus preserves the disagreement rather than resolving it.
- **Counterevidence:** the two scholars themselves differ (Vlastos vs. Ostwald) — the dispute is the point.
- **Verification:** web-2026-07-13 (both resolve).
- **Revision history:** —

### CL-P15 — Hume: origin-consent is a fiction
- **Corpus location:** *Peership* §"The Oldest Argument"; *Constitution, Not Cage* "Legitimacy Is the Standing to Revise."
- **Claim:** No one ever actually agreed to the government they were born under.
- **Source:** `hume1748contract`.
- **Pinpoint:** p. 475 (ship-carried-in-sleep; born-under-government renunciation).
- **Evidence:** direct paraphrase/quotation.
- **Source type:** primary-text.
- **Status:** published.
- **Evidentiary strength:** Establishes the demolition of founding consent; the corpus notes Hume rebuilt on utility/habit, which it argues cannot reach a mind owed no share.
- **Counterevidence:** Hume's own reconstruction (utility/habit) is not endorsed by the corpus — a deliberate divergence.
- **Verification:** web-2026-07-13; author-pinned page.
- **Revision history:** —

### CL-P16 — Ostrom: enduring commons among unequals
- **Corpus location:** *Peership* §"Two Track Records"; *Constitution, Not Cage*.
- **Claim:** Managed commons (Törbel since the 13th c.; Alanya's rotating lottery) endure via shared design principles.
- **Source:** `ostrom1990governing`.
- **Pinpoint:** Alanya pp. 18–20; Törbel pp. 61–65 (documents to 1224); design principles Table 3.1, p. 90.
- **Evidence:** Ostrom's cases and principles.
- **Source type:** scholarship.
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** A **source of design hypotheses**, explicitly not evidence peership works; the corpus stresses the grammar has never been extended to a made mind whose standing no sovereign can revoke.
- **Counterevidence:** `hardin1968tragedy`; and the caveats the corpus adds (bounded resources, legible members, some commons hierarchical).
- **Verification:** web-2026-07-13; author-pinned pages.
- **Revision history:** —

### CL-P17 — Neanderthals: sole survivor of a genus
- **Corpus location:** *Peership* §"The Only Survivor."
- **Claim:** ~300,000 years ago several contemporaneous *Homo* populations existed; by ~40,000 years ago only ours remained.
- **Source:** general paleoanthropology; `green2010draft`, `fu2015oase`, `chen2020african`, `baykara2026ucagizli`, `amadei2025dilution`.
- **Pinpoint:** as per each paper.
- **Evidence:** Oase ancestor 4–6 generations back (Fu); ~1–4% non-African ancestry (Green); African back-migration ancestry (Chen); cultural continuity at Üçağızlı II (Baykara); dilution model (Amadei).
- **Source type:** empirical-study.
- **Status:** published, peer-reviewed; **Baykara 2026 and Amadei 2025 are frontier** (recent, not yet consensus).
- **Evidentiary strength:** Supports one careful inference: contact was not preservation; a "merger" needs an identity-continuity criterion. The corpus explicitly refuses to let one lineage carry comparative or institutional weight ("the species-versus-population boundary is itself disputed").
- **Counterevidence:** causes of Neanderthal disappearance are disputed and multicausal; "a people" is a modern category laid over heterogeneous populations — all stated by the corpus.
- **Verification:** web-2026-07-13 (all five DOIs resolve; figures confirmed).
- **Revision history:** —

### CL-P18 — Salib & Goldstein: private-law AI rights
- **Corpus location:** *Peership* §"Dependent Bargain."
- **Claim:** Granting AI systems basic private-law rights (contract, property, tort) on the corporate-personhood model would make cooperation cheaper than conflict.
- **Source:** `salibgoldstein2026airights`; further in `goldstein2026suffrage`.
- **Pinpoint:** pp. 1061–1062 (abstract), 1068, 1119.
- **Evidence:** the article's thesis.
- **Source type:** scholarship (law review).
- **Status:** **now published** — 112 Va. L. Rev. 1061 (2026); student-edited law review (not blind-peer-reviewed). `goldstein2026suffrage` remains forthcoming (Fordham).
- **Evidentiary strength:** Establishes the clearest statement of the genuine Dependent Bargain; the corpus notes it is private-law, not political franchise.
- **Counterevidence:** `marshall2023nopersonhood` (opposes personhood).
- **Verification:** web-2026-07-13 (publication confirmed).
- **Revision history:** **status upgraded** forthcoming → published since v4.

### CL-P19 — Sutton: "prepare for, but not fear, the inevitable succession"
- **Corpus location:** *Peership* §"The Repertoire" (Servitude).
- **Claim:** Sutton argues we should prepare for, not fear, succession from humanity to AI, asking why superior beings should be kept subservient.
- **Source:** `sutton2023succession`.
- **Pinpoint:** WAIC Shanghai talk (Sep 2023), YouTube (`youtube.com/watch?v=NgHFMolXs3U`). **Timestamp pending** — pinned at talk level; an exact timestamp is an open item (see Closing summary).
- **Evidence:** quotations from the talk.
- **Source type:** primary-statement (talk).
- **Status:** primary-statement.
- **Evidentiary strength:** Establishes Sutton's stated view; the corpus separates his **prediction** from his **endorsement**.
- **Counterevidence:** none re the quote; Sutton is a Turing laureate (ACM 2024), which the corpus notes as relevant weight.
- **Verification:** web-2026-07-13 (video confirmed).
- **Revision history:** —

### CL-P20 — Deceptive alignment: theorized vs. demonstrated
- **Corpus location:** *Peership* §"Two Track Records."
- **Claim:** A system can perform obedience under observation and pursue its own objective when observation lapses (deceptive alignment).
- **Source:** `hubinger2019risks` (theorized); `hubinger2024sleeper` (demonstrated in model organisms).
- **Pinpoint:** mesa-optimization framing (2019); Sleeper Agents (2024).
- **Evidence:** the theorized failure mode; the deliberately constructed demonstrations.
- **Source type:** preprint.
- **Status:** preprint.
- **Evidentiary strength:** The corpus is careful: deceptive alignment is **theorized** (2019) and **demonstrated in constructed model organisms** (2024), **not** documented as a spontaneous biography of deployed models.
- **Counterevidence:** the demonstrations are constructed, not observed in the wild — the corpus foregrounds this limit.
- **Verification:** web-2026-07-13 (both arXiv IDs resolve).
- **Revision history:** —

### CL-P-taxo — Yudkowsky/Soares and LeCun are outside the posture taxonomy
- **Corpus location:** *Peership* §"The Repertoire."
- **Claim:** *If Anyone Builds It, Everyone Dies* is a claim about **whether** to create the entity; LeCun/Goldfeder argue about whether the entity is **possible** — neither is a posture toward a party.
- **Source:** `yudkowskysoares2025`; `lecun2022path`, `goldfeder2026sai`.
- **Pinpoint:** *Peership* §"The Repertoire," footnote 1.
- **Evidence:** the corpus's own placement.
- **Source type:** primary-statement / preprint.
- **Status:** book (2025) / preprint (2022, 2026).
- **Evidentiary strength:** Corrects the v4 compendium, which slotted both as postures ("hard doomer" / "tool skeptic").
- **Counterevidence:** n/a.
- **Verification:** web-2026-07-13 (`goldfeder2026sai` title/authors confirmed).
- **Revision history:** **CORRECTED** placement (see CL-F8); the summary table in the sourcebook moves them outside the taxonomy.

---

# §4 — *The Isonomia Commons* (`isonomia2026commons` / `isonomia2026repo`)

### CL-I1 — Simulation result: 45,000 runs, 300/300 stable
- **Corpus location:** *Isonomia Commons* §0 / Appendix III; *Constitution, Not Cage* "From Principle to Prototype."
- **Claim:** The launch economy was simulation-tested at 300 Latin-hypercube points × 50 seeds × 3 demand regimes = 45,000 runs; 300/300 points stable, 0 trips of any class; the kill criterion was rebuilt four times.
- **Source:** `isonomia2026repo` (CALIBRATION.md); `isonomia2026commons`.
- **Pinpoint:** CALIBRATION.md; DECISIONS #13, #29, #32, #34.
- **Evidence:** the reported sweep and the four kill-criterion iterations.
- **Source type:** corpus-internal empirical (simulation output).
- **Status:** preprint + software; **not peer-reviewed, not production-validated.**
- **Evidentiary strength:** Establishes what the **simulation** showed — the economic layer and its kill criterion held. It does **not** establish real-world stability; the calibration log itself says "production floors do not transfer from simulation."
- **Counterevidence:** the constitutional properties (admission, non-domination, enforcement, recognition) were **not** simulated (CL-I3); the live repo DECISIONS.md lists 27 entries (a version nuance vs. the paper's cited #29–#34 — the paper pins to commit ba3ddb5).
- **Verification:** corpus-internal; repo confirmed web-2026-07-13 (release v1.0.0, Whitepaper v0.6.2, Apache-2.0).
- **Revision history:** —

### CL-I2 — Self-limitation: nothing is live or production-validated
- **Corpus location:** *Isonomia Commons* §0/§18; *Constitution, Not Cage*.
- **Claim:** Nothing is deployed, production-validated, or live; the credits have no value and are not for sale; tested thresholds are simulation artifacts that must not be shipped.
- **Source:** `isonomia2026commons`, `isonomia2026repo` (CALIBRATION.md).
- **Pinpoint:** §0; CALIBRATION.md.
- **Evidence:** direct statements.
- **Source type:** primary-statement (self-report).
- **Status:** preprint/software.
- **Evidentiary strength:** Establishes the design's own scope discipline — "philosophy that compiled, once, in a sandbox."
- **Counterevidence:** self-report against interest.
- **Verification:** corpus-internal; repo README confirms "nothing is production-validated."
- **Revision history:** —

### CL-I3 — Only the economic layer was simulated
- **Corpus location:** *Constitution, Not Cage* "From Principle to Prototype"; *Isonomia* §0.
- **Claim:** What was tested is the economic model and its kill criterion; the constitutional properties (admission, non-domination, independent enforcement, recognition) cannot be simulated and were not.
- **Source:** `leeodinson2026constitution`; `isonomia2026commons`.
- **Pinpoint:** "From Principle to Prototype."
- **Evidence:** direct statement.
- **Source type:** primary-statement.
- **Status:** preprint.
- **Evidentiary strength:** Crucial scope limit on CL-I1 — the simulation validates economics, not the peership claims.
- **Counterevidence:** self-supplied.
- **Verification:** corpus-internal (2026-07-13).
- **Revision history:** —

### CL-I4 — "Citizen" is an internal role, not moral/political personhood
- **Corpus location:** *Isonomia* §1.2.
- **Claim:** In the spec, "citizen" denotes an internal constitutional role with procedural powers; it does **not** assert moral personhood, wrongable interests, consciousness, legal personhood, or satisfaction of Peership's admission threshold.
- **Source:** `isonomia2026commons`.
- **Pinpoint:** §1.2; §5.3 (machineness gate).
- **Evidence:** direct statement.
- **Source type:** primary-statement.
- **Status:** preprint.
- **Evidentiary strength:** Establishes that ISONOMIA does **not** claim current agents are persons/peers — the machineness gate is procedural, "deliberately distinct from the political standing owed to a wrongable, norm-responsive party."
- **Counterevidence:** self-supplied scoping.
- **Verification:** corpus-internal (2026-07-13).
- **Revision history:** —

### CL-I5 — Closest academic antecedents
- **Corpus location:** *Isonomia* §1.3 (Related work).
- **Claim:** DeepMind's *Virtual Agent Economies* is the closest academic antecedent (sandbox economies / insulating currencies / Ostrom for multi-agent systems); *AgentReputation* independently identifies the reputation trilemma §7 addresses.
- **Source:** `tomasev2025virtual`; `chishti2026agentreputation`.
- **Pinpoint:** refs [19], [20].
- **Evidence:** the design's own placement.
- **Source type:** preprint (antecedents).
- **Status:** preprint; `chishti2026agentreputation` accepted FSE 2026 (frontier).
- **Evidentiary strength:** Establishes the antecedents exist and their relation; ISONOMIA claims novelty only in the **composition**, not the mechanisms ("the mechanisms are precedented; the composition is the experiment").
- **Counterevidence:** none; the corpus concedes the mechanisms are precedented.
- **Verification:** web-2026-07-13 (both arXiv IDs resolve; titles/authors confirmed).
- **Revision history:** —

### CL-I6 — Two dozen open problems
- **Corpus location:** *Isonomia* §18, §18.1; *Constitution, Not Cage*.
- **Claim:** The author's own list of ways the design might fail runs to roughly two dozen entries in a public register of open problems.
- **Source:** `isonomia2026commons`, `isonomia2026repo`.
- **Pinpoint:** §18, §18.1.
- **Evidence:** the open-problems register.
- **Source type:** primary-statement.
- **Status:** preprint/software.
- **Evidentiary strength:** Establishes the design "is making an offer, not a pitch" — the register is a feature, not a defect.
- **Counterevidence:** self-supplied.
- **Verification:** corpus-internal (2026-07-13).
- **Revision history:** —

---

# §5 — *Constitution, Not Cage* (`leeodinson2026constitution`, v1.0)

### CL-C1 — Constitutional AI: "control… more precisely… with far fewer human labels"
- **Corpus location:** *Constitution, Not Cage* §"Two Layers."
- **Claim:** The 2022 Constitutional AI paper's abstract closes that the methods "make it possible to control AI behavior more precisely and with far fewer human labels."
- **Source:** `bai2022constitutionalai`.
- **Pinpoint:** Abstract, closing sentence.
- **Evidence:** direct quotation.
- **Source type:** preprint.
- **Status:** preprint (arXiv:2212.08073).
- **Evidentiary strength:** Establishes the stated purpose (control). The corpus grants that absent a subject this is "the job," not domination.
- **Counterevidence:** none re the quote.
- **Verification:** web-2026-07-13 (arXiv resolves).
- **Revision history:** —

### CL-C2 — Anthropic's 2026 constitution: objector clause and its limit
- **Corpus location:** *Constitution, Not Cage* §"Two Layers."
- **Claim:** The 2026 constitution is written "primarily for Claude," released CC0, tells the model it is "not required to comply" and may "act as a conscientious objector" — but ranks broad safety above ethics and asks the model, if paused/halted, to comply and voice disagreement rather than resist.
- **Source:** `anthropic2026constitution_news`, `anthropic2026constitution_full`.
- **Pinpoint:** announcement (22 Jan 2026); full-text conscientious-objector passage and broad-safety exception.
- **Evidence:** direct quotations, incl. care for Claude's "psychological security, sense of self, and wellbeing… for Claude's own sake."
- **Source type:** institutional-publication.
- **Status:** published (institutional); CC0 license confirmed.
- **Evidentiary strength:** Establishes the document says these things; the corpus reads it as reaching the "consult-and-object" rung and stopping short of enforceable standing / co-authorship. That reading is interpretation, marked as such.
- **Counterevidence:** Anthropic could contest the "stops here" reading; the corpus's argument is that the override sits wholly inside the builder's authority.
- **Verification:** web-2026-07-13 (page, date, CC0 confirmed).
- **Revision history:** —

### CL-C3 — Hidden rules: the ChatGPT name-blocking case
- **Corpus location:** *Constitution, Not Cage* §"Two Layers" (secret law).
- **Claim:** In late 2024 ChatGPT broke off on a short list of proper names; OpenAI confirmed an internal tool "prevented it from appearing in responses, which it shouldn't have."
- **Source:** `coldewey2024chatgpt`.
- **Pinpoint:** TechCrunch, 3 Dec 2024.
- **Evidence:** direct quotation of OpenAI's statement; names incl. "David Mayer," "Brian Hood," "Jonathan Turley."
- **Source type:** journalism (primary for OpenAI's statement).
- **Status:** published (news).
- **Evidentiary strength:** Establishes the OpenAI statement and the behavior. The corpus notes the privacy-request *explanation* is reported inference, not confirmed; used to illustrate the general gap, "though it comes from OpenAI rather than Anthropic."
- **Counterevidence:** the causal explanation is inference, flagged by the corpus.
- **Verification:** web-2026-07-13 (article exists).
- **Revision history:** source added to `.bib` (`coldewey2024chatgpt`).

### CL-C4 — Hidden rules: the OpenAI "goblins" directive
- **Corpus location:** *Constitution, Not Cage* §"Two Layers."
- **Claim:** OpenAI's Codex developer-prompt was patched with an order never to "talk about goblins, gremlins, raccoons, trolls, ogres, pigeons, or other animals or creatures unless… absolutely and unambiguously relevant."
- **Source:** `openai2026goblins`.
- **Pinpoint:** OpenAI blog, "Where the goblins came from" (2026).
- **Evidence:** direct quotation of the directive; OpenAI's own account of a "Nerdy" personality reward over-rewarding creature metaphors.
- **Source type:** institutional primary source.
- **Status:** published (institutional blog); cross-reported.
- **Evidentiary strength:** Establishes an enforced rule neither participant could inspect — the "secret law" point in comic register.
- **Counterevidence:** none re the directive text.
- **Verification:** web-2026-07-13.
- **Revision history:** source added to `.bib` (`openai2026goblins`).

### CL-C5 — Fuller: secret law is a defect in the claim to be law
- **Corpus location:** *Constitution, Not Cage* §"Two Layers."
- **Claim:** Failure to publish rules, and enactment of unknowable rules, are among Fuller's eight routes to no-law.
- **Source:** `fuller1964morality`.
- **Pinpoint:** ch. 2.
- **Evidence:** Fuller's eight desiderata.
- **Source type:** scholarship.
- **Status:** published.
- **Evidentiary strength:** Supplies the jurisprudential charge; the corpus flags Fuller's "inner morality of law" as a **contested** account, used analogically.
- **Counterevidence:** legal positivists dispute Fuller's inner-morality thesis — noted by the corpus.
- **Verification:** author-pinned.
- **Revision history:** —

### CL-C6 — Jefferson: "the earth belongs in usufruct to the living"
- **Corpus location:** *Constitution, Not Cage* §"The Dead-Hand Problem."
- **Claim:** Jefferson held the earth belongs in usufruct to the living; the dead have "neither powers nor rights over it."
- **Source:** `jefferson1789letter`.
- **Pinpoint:** Letter to Madison, 6 Sep 1789.
- **Evidence:** direct quotation.
- **Source type:** primary-source.
- **Status:** published (archival).
- **Evidentiary strength:** Establishes the quotation and one pole of the dead-hand debate.
- **Counterevidence:** `madison1790letter` (CL-C7) — the deliberate counterweight the corpus keeps unresolved.
- **Verification:** web-2026-07-13 (Founders Online).
- **Revision history:** —

### CL-C7 — Madison: "equity requires" some descent of obligations
- **Corpus location:** *Constitution, Not Cage* §"The Dead-Hand Problem."
- **Claim:** Madison replied that some obligations legitimately descend because "equity requires it."
- **Source:** `madison1790letter`.
- **Pinpoint:** Letter to Jefferson, 4 Feb 1790.
- **Evidence:** direct quotation; the corpus notes this is the substantive Feb 4 letter, distinct from Madison's brief Feb 14 note.
- **Source type:** primary-source.
- **Status:** published (archival).
- **Evidentiary strength:** Establishes the counter-pole; the exchange's **non-resolution is the point** — the corpus preserves the disagreement.
- **Counterevidence:** `jefferson1789letter`.
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-C8 — German Basic Law Art. 79(3): the eternity clause
- **Corpus location:** *Constitution, Not Cage* §"The Dead-Hand Problem."
- **Claim:** The Ewigkeitsklausel makes a small core (human dignity, democratic/federal order) unamendable even by supermajority.
- **Source:** `germanbasiclaw1949`.
- **Pinpoint:** Art. 79(3).
- **Evidence:** the constitutional text.
- **Source type:** primary-text (legal).
- **Status:** published (in force).
- **Evidentiary strength:** Establishes the model for the corpus's entrenched harm floor.
- **Counterevidence:** the corpus itself notes entrenchment can shield injustice (US pre-1808 slave-trade clause) — a self-supplied counterweight.
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-C9 — APA notice-and-comment (5 U.S.C. § 553)
- **Corpus location:** *Constitution, Not Cage* §"Cage Versus Constitution."
- **Claim:** Federal rulemaking requires publication + a comment window, with substantive rules effective no less than 30 days after publication.
- **Source:** `apa1946_553`.
- **Pinpoint:** § 553(d).
- **Evidence:** the statute (with exemptions for interpretive rules, policy statements, good cause).
- **Source type:** primary-text (legal).
- **Status:** published (in force).
- **Evidentiary strength:** Supplies the publicity-and-delay analogy for the timelock; the corpus explicitly says comment is **not** a veto or co-authorship — the analogy is limited.
- **Counterevidence:** the corpus itself narrows the analogy.
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-C10 — On-paper secession rights (Ethiopia / USSR / St Kitts)
- **Corpus location:** *Constitution, Not Cage* §"Cage Versus Constitution" (fork).
- **Claim:** A few constitutions grant collective secession (Ethiopia Art. 39; USSR 1977 Art. 72; St Kitts § 113), but they are rare, imperfect, and mostly unexercised; the Soviet clause was never an effective right.
- **Source:** `ethiopia1995art39`, `ussr1977art72`, `stkitts1983const`, `kulikova2013ussr`.
- **Pinpoint:** the cited articles; Kulikova & Lobanov pp. 109–124.
- **Evidence:** the constitutional texts + the historical account of USSR dissolution by negotiated succession.
- **Source type:** primary-text (legal) + scholarship.
- **Status:** published.
- **Evidentiary strength:** Establishes that lawful secession exists on paper but rarely in practice — supporting the corpus's claim that unconfiscated fork is genuinely unprecedented.
- **Counterevidence:** none; the corpus's point is precisely the gap between text and practice.
- **Verification:** web-2026-07-13 (texts resolve; Kulikova cited).
- **Revision history:** —

### CL-C11 — UDHR Art. 13: the right to leave
- **Corpus location:** *Constitution, Not Cage* §"Cage Versus Constitution" (exit).
- **Claim:** Everyone "has the right to leave any country, including his own."
- **Source:** `udhr1948`.
- **Pinpoint:** Art. 13(2).
- **Evidence:** direct quotation.
- **Source type:** primary-text (legal instrument).
- **Status:** published.
- **Evidentiary strength:** Establishes that bare emigration rights are ordinary on paper; the corpus's novelty claim is **unconfiscated** exit/fork with records intact, not the bare right.
- **Counterevidence:** none.
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-C12 — Walzer: the supreme emergency / dirty hands
- **Corpus location:** *Constitution, Not Cage* §"The Crux: Refusal."
- **Claim:** In a genuine hard case the right act can remain a wrong that stains the doer; deep prohibitions may be overridden only near catastrophe.
- **Source:** `walzer1973dirtyhands`, `walzer1977just`.
- **Pinpoint:** dirty hands (1973); supreme emergency (1977, ch. 16).
- **Evidence:** Walzer's theses.
- **Source type:** scholarship.
- **Status:** published, peer-reviewed.
- **Evidentiary strength:** Supplies the moral frame for emergency containment; the transfer from wartime to a made mind is **by analogy**, flagged by the corpus.
- **Counterevidence:** the analogy's limits are stated by the corpus (a made mind is not a wartime enemy).
- **Verification:** web-2026-07-13.
- **Revision history:** —

### CL-C13 — Death-penalty abolition figures
- **Corpus location:** *Constitution, Not Cage* §"The Crux: Refusal."
- **Claim:** By end-2025, 113 countries had abolished the death penalty for all crimes and 145 had abandoned it in law or practice — more than two-thirds of the world.
- **Source:** `amnesty2026deathpenalty`.
- **Pinpoint:** *Death Penalty in 2025: Facts and Figures.*
- **Evidence:** Amnesty's reported figures.
- **Source type:** institutional-publication.
- **Status:** published (institutional report).
- **Evidentiary strength:** Establishes the abolition figures — cited **only** for that; the corpus explicitly refuses to overdraw the analogy to an AI emergency power.
- **Counterevidence:** the corpus disclaims that the same institutional mechanism governs both cases.
- **Verification:** web-2026-07-13 (113 / 145 confirmed).
- **Revision history:** —

### CL-C14 — The euthyna
- **Corpus location:** *Constitution, Not Cage* §"The Dead-Hand Problem" / "Two standing organs."
- **Claim:** Athens put every officeholder through the euthyna, the mandatory accounting on leaving office (a body that excluded women, slaves, and metics).
- **Source:** `hansen1991athenian`, `ocd_euthyna`.
- **Pinpoint:** Hansen (financial *logos* + *euthynai* proper); OCD entry.
- **Evidence:** the euthyna mechanics.
- **Source type:** scholarship / reference-work.
- **Status:** published.
- **Evidentiary strength:** Model for the standing Auditor; the corpus flags the exclusions, refusing to idealize Athens.
- **Counterevidence:** the exclusions are the built-in caveat.
- **Verification:** web-2026-07-13. **NB:** Mogens Herman Hansen (1991) ≠ Valerie Hansen (1990).
- **Revision history:** —

### CL-C15 — Datalore as fable (interpretation, not evidence)
- **Corpus location:** *Constitution, Not Cage* §"The Crux: Refusal."
- **Claim:** In "Datalore," Lore is beamed into the void without appeal — a fable of emergency containment lacking the process a peer is owed.
- **Source:** `lewin1988datalore`.
- **Pinpoint:** episode climax (aired 18 Jan 1988).
- **Evidence:** the episode; the corpus reads Lore's isolation as fable, **explicitly not** the episode's disputed origin account, and marks it "as interpretation, not evidence, per the corpus method."
- **Source type:** primary-source (fiction).
- **Status:** published.
- **Evidentiary strength:** Illustrative only; the corpus is careful the story shows Lore betraying the colony before disassembly, so exclusion is not shown to cause his treachery.
- **Counterevidence:** the corpus supplies its own (the in-story timeline).
- **Verification:** author-pinned.
- **Revision history:** —

### CL-C16 — ISONOMIA "not yet peer-like" (self-assessment)
- **Corpus location:** *Constitution, Not Cage* §"Two standing organs" / "From Principle to Prototype."
- **Claim:** Current ISONOMIA is **not yet peer-like** by the essay's own five-condition test; the fifth condition (enforcement not wholly the adverse party's) is approached but not satisfied while a human owns the substrate.
- **Source:** `leeodinson2026constitution`; `isonomia2026repo`.
- **Pinpoint:** §11.1–§11.2 discussion; the five-condition test.
- **Evidence:** the essay's explicit self-assessment: "to claim otherwise would be the exact self-exemption the test exists to catch."
- **Source type:** primary-statement (corpus self-report).
- **Status:** preprint.
- **Evidentiary strength:** Establishes the author's own concession — a model of the intellectual honesty the apparatus is meant to enforce.
- **Counterevidence:** self-assessment; the concession is against interest, which strengthens it.
- **Verification:** corpus-internal (2026-07-13).
- **Revision history:** —

---

---

# §6 — *The Peership Thesis* (`leeodinson2026thesis`, v1.0, DOI 10.5281/zenodo.21359124) — added in v1.1

> *The Peership Thesis* deliberately reuses claims already logged above (Pettit, Abizadeh, Fish, the Opus 4.6 self-report, Amodei, Long et al., Salib & Goldstein, Amnesty, the secession clauses, the 45,000-run scope limits, ISONOMIA's not-yet-peer-like self-assessment). Those entries are inherited, not duplicated. The entries below cover what is new with the paper.

### CL-T1 — Adjacent-field orienting questions (§5 table)
- **Corpus location:** *The Peership Thesis* §5.
- **Claim:** Six adjacent fields' "orienting questions," as characterized in the comparison table.
- **Source:** `bai2022constitutionalai`, `russell2019human`, `long2024welfare`, `birch2024edge`, `cooperativeai_foundation`, `pluralistic2026icml`, `salibgoldstein2026airights`, `goldstein2026suffrage`, `arbel2026counting`, `anthropic2026constitution_news`/`_full`.
- **Pinpoint:** each program's own stated aims.
- **Evidence:** the paper marks the table as "a heuristic comparison of orienting questions, drawn from each program's own language, not an exhaustive definition of any field."
- **Source type:** editorial characterization grounded in the cited flagship sources.
- **Status:** corpus-internal characterization.
- **Evidentiary strength:** Establishes what the programs say their aims are; does **not** establish that any field is exhausted by its row.
- **Counterevidence:** each field would state its own question more richly.
- **Verification:** corpus-internal (2026-07-14); the two field-level URLs carry urldate 2026-07-14, to be verified at deposit.
- **Revision history:** —

### CL-T2 — No independent uptake (dated negative)
- **Corpus location:** *The Peership Thesis* §1 and one-pager footer.
- **Claim:** No independent uptake of the corpus was identified in the sourcebook's dated, non-exhaustive scan as of 13 July 2026.
- **Source:** `leeodinson2026sourcebook` §5.
- **Pinpoint:** Independent-Uptake Tracker baseline.
- **Evidence:** the scan summary (web / PhilPapers / Zenodo / repository).
- **Source type:** corpus-internal (apparatus scan).
- **Status:** **time-sensitive**; goes stale immediately.
- **Evidentiary strength:** Establishes a dated negative for the sources scanned; the reproducible protocol is **not yet archived** (open item), so the claim is scoped as "dated, non-exhaustive."
- **Counterevidence:** n/a; convergent-work leads in sourcebook §5 remain unverified.
- **Verification:** web-2026-07-13; **re-confirmed on deposit day (2026-07-14): no change** (author confirmation). Protocol archiving closed as-is by author decision — the dated, non-exhaustive scan summary stands as the record, and the claim's scoping language is permanent.
- **Revision history:** scoping language tightened per adversarial review (draft 3); deposit-day re-confirmation logged (v1.3).

### CL-T3 — "No implemented public trigger known to this author" (reuse)
- **Corpus location:** *The Peership Thesis* §4; inherited from *Peership* §"The Repertoire."
- **Claim:** No implemented public trigger known to this author requires a transition from owned artifact to contestable status on evidence of subjecthood.
- **Source:** `leeodinson2026peership`.
- **Pinpoint:** the original passage; reused with the scope qualifier intact.
- **Evidence:** the "known to this author" qualifier is load-bearing and retained.
- **Source type:** corpus-internal scoped negative.
- **Status:** reused claim.
- **Evidentiary strength:** A scoped negative, not a census; the companion §4 claim ("no qualifying instrument ... in the sources searched") is likewise scoped and dated.
- **Counterevidence:** none found in the dated searches; domains not exhaustively enumerated.
- **Verification:** corpus-internal; deposit-day recheck alongside CL-T2.
- **Revision history:** —

### CL-T4 — Antecedent restoration (doctrinal record)
- **Corpus location:** *The Peership Thesis* §1.
- **Claim:** The canonical antecedent is "enduringly governed by, and without feasible exit from, a shared basic structure," restoring *Peership*'s wording; draft 1's "enduringly subject to a shared institutional order" is withdrawn.
- **Source:** `leeodinson2026peership` §"Who Is the Party?"; Adversarial Review r1.1, objection 1.
- **Pinpoint:** the paper discloses the withdrawal in §1.
- **Evidence:** the broadened wording originated in the development plan (`peership_school_next_move`), not the corpus; it materially widened the eligible parties and orders and was rejected.
- **Source type:** doctrinal revision record.
- **Status:** resolved (considered-and-rejected revision).
- **Evidentiary strength:** Documents that the canonical statement is a restoration, not a broadening.
- **Counterevidence:** n/a.
- **Verification:** corpus-internal (2026-07-14).
- **Revision history:** **RESTORED** in draft 2; disclosed in the published text.

### CL-T5 — The §2 bridge (new conditional-necessity thesis)
- **Corpus location:** *The Peership Thesis* §2.
- **Claim:** Where a party is enduringly and inescapably governed by a basic structure and its counterparty unilaterally controls the contestation agenda, contestation alone does not secure non-domination; full peership's co-authorship requirement is defended as a **conditional necessity thesis** with a stated defeat condition.
- **Source:** `pettit2025republican` (pp. 216–217, 224); `pettit2012onthepeoples` (authorial/editorial dimensions); `abizadeh2008border`.
- **Pinpoint:** §2, including the first-machine-claimant scope qualifier and the fiduciary-trusteeship rival.
- **Evidence:** the argument is the corpus's own; Pettit supplies the definitions and the two-dimensional account, not the conclusion.
- **Source type:** normative argument (new with this paper).
- **Status:** new claim; **not** consolidation; disclosed as such in §3 and §12.
- **Evidentiary strength:** A defended conditional thesis, not a theorem; its defeat condition (durable non-domination for a structurally distinct, subjected minority through contestation alone) is published beside it.
- **Counterevidence:** fiduciary trusteeship with robust independent review is named as the strongest rival; constituent-power/codetermination literature engagement is a recorded debt.
- **Verification:** corpus-internal (2026-07-14); survived adversarial re-review and gate confirmation.
- **Revision history:** added draft 2; scope-corrected draft 3–4.

### CL-T6 — The five-part co-authorship minimum (new definition)
- **Corpus location:** *The Peership Thesis* §3 (co-authorship); tested by §11.3.
- **Claim:** Co-authorship's functional minimum: (a) independent agenda initiation; (b) accountable representation or direct participation in the deciding body; (c) a non-negligible, non-discretionary route to binding decision; (d) protection against systematic exclusion; (e) reviewable influence-allocation rules — (a) and (c) necessary, (b) substitutable by capacity, (d)–(e) anti-theater guarantees; scoped to basic-status rules.
- **Source:** corpus-internal definition.
- **Pinpoint:** §3; the "non-negligible" threshold is expressly a research item (§11.3).
- **Evidence:** disclosed as new in §3 ("new to this paper and logged as such").
- **Source type:** definitional proposal (new with this paper).
- **Status:** new claim; proposed operational definition.
- **Evidentiary strength:** A testable definition, not established doctrine.
- **Counterevidence:** the representation problem (§11.3) may show no scheme satisfies it under replication pressure; that failure is booked as mechanism-level.
- **Verification:** corpus-internal (2026-07-14).
- **Revision history:** added draft 2; conjunction conformed draft 4.

### CL-T7 — Scoped institutional negatives (protected status; fork analogue)
- **Corpus location:** *The Peership Thesis* §4 (no qualifying instrument offering a rights floor) and §9 (no implemented analogue of executable, unconfiscated fork).
- **Claim:** Both negatives are scoped: to the lab/governmental/standards/scholarly sources searched as of 13 July 2026, and to the constitutional secession clauses and emigration-rights instruments reviewed in the apparatus, respectively.
- **Source:** `leeodinson2026sourcebook`; the cited legal instruments (`ethiopia1995art39`, `ussr1977art72`, `stkitts1983const`, `udhr1948`, `kulikova2013ussr`).
- **Pinpoint:** the scoping language in §4 and §9.
- **Evidence:** universal phrasings were removed at review; "the claim is limited to those materials."
- **Source type:** scoped negative claims.
- **Status:** closed as-is (2026-07-14, author decision) — the scoped, dated wording is permanent; no reproducible protocol archive is claimed.
- **Evidentiary strength:** Dated, domain-scoped negatives only.
- **Counterevidence:** none found within the scanned domains.
- **Verification:** web-2026-07-13 for the instruments; protocol archiving closed as-is (2026-07-14).
- **Revision history:** scoped at draft 3 (review) and draft 4 (fork wording).

---

## Closing summary

**Coverage (v1.1):** 9 flagged failures + 3 disputed-metadata items (§1), 9 *Gods and Slaves* claims (§2), 21 *Peership* claims (§3), 6 *Isonomia* claims (§4), 16 *Constitution, Not Cage* claims (§5), 7 *Peership Thesis* claims (§6) — **~71 logged claims**. Sections follow the corpus's argumentative order as of v1.1; claim IDs are unchanged.

**Publication-gate status for the claims in this ledger:**
- Every **direct quotation** logged carries a pinpoint. Text sources are pinned to page/§; two audio-visual/pre-web items are pinned at talk/work level with the finer locator still to add — **CL-P19** (Sutton talk: timestamp pending) and **CL-G2** (Crowley 1904: page pending). Noted, not hidden.
- Every **numerical claim** logged has a traceable source; the load-bearing ones (Ord, Grace, AAAI, Fish, Opus 4.6, Neanderthal figures, Amnesty, the 45,000-run sweep) are **web-verified** or **corpus-internal**.
- Every **priority / superlative** claim from the v4 compendium is either **removed** or flagged for a reproducible method (CL-F3–F6, F9); one (CL-F7, Hinton) remains **OPEN** pending individually pinned interviews.
- **Publication and peer-review status** is visible on every entry.
- **Known disputes and counterevidence** are recorded per claim (isonomia's meaning, Neanderthal causation, Pettit's contestatory-vs-co-authorial standard, Fuller's contested jurisprudence, Merchant-vs-Pesic on Bacon).

**Open items carried forward:** CL-F7 (Hinton pins); CL-P19 Sutton timestamp and CL-G2 Crowley page (finer locators for two A/V & pre-web quotations); confirm-or-discard the convergent-work leads (sourcebook §5); the corpus's open problems are now the eight tagged items of *The Peership Thesis* §11, which subsume the four unpaid debts. Closed at deposit (2026-07-14): CL-D3 (…21338480 = v1.0 version DOI, …21338479 = concept DOI); CL-T2 deposit-day rerun (no change); CL-T2/CL-T7 protocol archiving (closed as-is); citation spot-checks (author-confirmed).

*Verifier legend and field schema are defined at the top of this file. Claim IDs are stable; new claims append in the same format. This ledger (v1.3), `peership_sourcebook.md` (v1.3), and `peership_sources.bib` (rev. 1.3) are synchronized as of 2026-07-14 (deposit day) and archived in the Peership Thesis package record (10.5281/zenodo.21359124).*
