> ## Editorial note — added when this record was committed to the corpus repository
>
> This document is committed **as supplied**. The text below the rule is unaltered. Three things a reader must
> carry into it:
>
> 1. **The reviewer prompt in §4 is a RECONSTRUCTION, not a transcript.** The document says so itself, and the
>    point is important enough to repeat here: the original ISONOMIA review prompt **was never preserved**. It
>    must not be read as the instruction a reviewer actually received, and it must not be compared like-for-like
>    with the *real* prompts published for [*Peership*](../02-peership/) and [*The Peership Thesis*](../05-peership-thesis/),
>    which are verbatim.
>
> 2. **§13's DOI table contains an error.** It gives the preprint **concept DOI** as `10.5281/zenodo.21338480`.
>    It is not. Per the Zenodo REST API (captured in [`../../apparatus/verification/`](../../apparatus/verification/))
>    and claim-ledger entry **CL-D3**:
>    - `10.5281/zenodo.21338479` — concept (all-versions) DOI
>    - `10.5281/zenodo.21338480` — **v1.0 exact-version** DOI
>    - `10.5281/zenodo.21343917` — v1.1 exact-version DOI (the deposited version)
>
>    The error is the same one carried by the ISONOMIA repository's own manifest. It is recorded, not patched, so
>    that the supplied record stays intact; see discrepancy **D5** in [`../../VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md).
>
> 3. **This is a process summary, not an independent peer review.** The document is explicit about that in §7 and
>    §12, and §12 in particular is worth reading before any of the achievements listed elsewhere.
>
> The controlling public attribution for reviewers across this corpus remains **"a model from a different
> laboratory"** — the narrower formulation this document itself recommends (§3) absent archived session records.

---

# The Isonomia Commons: Whitepaper Review and Audit Trail

**Author:** Dan Lee-Odinson  
**Project:** ISONOMIA / *The Isonomia Commons*  
**Audit scope:** Individual whitepaper development, adversarial-review history, DOI-preprint publication audit, and downstream repository claim-discipline controls  
**Audit compiled:** 14 July 2026  
**Status:** Process summary, not an independent peer-review report

## 1. Purpose of this record

This document records how *The Isonomia Commons: A Constitutional Design for Autonomous Agent Labor Markets* developed from an early speculative agent-economy proposal into a versioned constitutional design and DOI preprint.

It answers five questions:

1. What review method was used?
2. What reviewer prompt governed the adversarial review?
3. How many review cycles are documented?
4. What substantive changes resulted from those cycles?
5. What has—and has not—been validated?

The audit separates three processes that should not be conflated:

- **Whitepaper adversarial development:** the formal cycles that changed the design itself.
- **Preprint publication audit:** the later review that corrected corpus placement, packaging, citation, and empirical-claim language.
- **Repository integration and release audit:** the downstream check that synchronized the living documents, metadata, website, and release record without changing the simulation evidence.

Only the first process counts as the whitepaper's formal adversarial drafting cycles. The other two are additional publication and configuration controls.

---

## 2. Project identity and artifact model

**Current name:** ISONOMIA / *The Isonomia Commons*  
**Earlier working names:** AGORA; briefly STYLOS Commons  
**Current framing:** A mutual-credit labor exchange with self-governing institutions, staged by verifiability  
**Canonical corpus role:** One implementation hypothesis within Peership

The project maintains deliberately separate artifact tracks:

| Artifact | Purpose | Versioning rule |
|---|---|---|
| Living repository whitepaper | Current constitutional specification | Continues on the repository's own `v0.x` document sequence |
| DOI preprint | Frozen scholarly package | Uses its own package version sequence (`v1.0`, `v1.1`, etc.) |
| Repository release | Frozen code, data, documentation, and metadata snapshot | Uses GitHub/Zenodo software-release versions (`v1.0.0`, `v1.1.0`) |
| Simulation evidence baseline | Exact executable and results state | Remains pinned to the release and commit that produced the evidence |

The version numbers are not interchangeable. In particular:

- repository whitepaper `v0.6.3` is a living specification;
- the frozen preprint contains a whitepaper snapshot identified within the preprint package;
- software release `v1.1.0` is not “Whitepaper v1.1”;
- documentation corrections in software release `v1.1.0` did not create new empirical evidence.

---

## 3. Human–AI review workflow

The project used a human-directed, multi-model workflow:

| Role | Function |
|---|---|
| Claude (Anthropic) | Principal drafting, design implementation, document revision, and repository work |
| Rival-laboratory GPT model | Adversarial reviewer, skeptical auditor, cross-document checker, and publication-gate reviewer |
| Dan Lee-Odinson | Scope-setter, source selector, conflict resolver, authorial override, release authority, and sole accountable author |

Working audit notes identify GPT-5.5 as the principal adversarial reviewer during the early whitepaper process. The published provenance statement uses the narrower formulation “a model from a different laboratory.” That published wording should remain the controlling public attribution unless the underlying session records are archived with the project.

AI systems are not credited as authors. The whitepaper states the reason directly: they cannot bear responsibility for the work. Dan Lee-Odinson is the sole author and accepts responsibility for the claims, decisions, omissions, and release.

Repeated agreement between models was not treated as validation. The process sought stronger signals through:

- explicit assumptions;
- named dependencies;
- adversarial threat modeling;
- bounded claims;
- simulation-first testing;
- positive and negative controls;
- versioned specifications;
- correction histories;
- publication gates; and
- explicit registers of unresolved work and missing expertise.

---

## 4. Reviewer prompt used

### Preservation note

The exact verbatim prompt from the first whitepaper review was not preserved in the currently assembled artifact set. The following is a faithful operational reconstruction from the recorded review method, resulting revision categories, and later review instructions. It should be cited as a **reconstructed prompt**, not as a transcript.

### Reconstructed adversarial-review prompt

> Act as a hostile, expert adversarial reviewer of this whitepaper and its proposed launch design. Do not merely edit for style and do not reward novelty, ambition, candor, or AI-assisted drafting. Attack the strongest version of the proposal.
>
> Review simultaneously from the standpoint of a mechanism designer, economist, distributed-systems and security engineer, constitutional and institutional theorist, AI-alignment researcher, legal and regulatory analyst, implementation lead, and skeptical technical editor.
>
> Test the following areas hardest:
>
> 1. **Economic coherence:** issuance, settlement, mutual-credit invariants, pricing, credit limits, default, fee balance, reputation, monetary-policy capture, and whether any mechanism recreates ownership or profit under another name.
> 2. **Verification:** whether useful work can actually be verified; whether the proposal treats verification as a solved module; what classes of work can launch safely; and what fails under adversarial inputs.
> 3. **Identity and control:** Sybil resistance, copying, lineage, model updates, change of control, human puppeteering, beneficial ownership, key custody, and behavioral fingerprinting.
> 4. **Governance:** vote capture, plutocracy, monoculture, sortition failure, emergency powers, amendment, Auditor and Adversary corruption, self-preservation drift, fork, exit, and the difference between procedural voice and actual standing.
> 5. **Security and threat model:** wash trading, collusion, bribery, data poisoning, denial of service, malicious task payloads, provider coercion, legal seizure, external influence, and attacks against the detection system itself.
> 6. **Legal and regulatory exposure:** securities, payments, AML, sanctions, privacy, content liability, foundation form, jurisdiction, export controls, hosting dependence, and whether a legal wrapper becomes an owner in practice.
> 7. **Implementation honesty:** what is currently buildable; what depends on emerging or nonexistent technology; whether launch scope is falsifiable; whether parameter values are evidence or placeholders; and what should block deployment.
> 8. **Claim and citation discipline:** unsupported factual claims, priority claims, overstatement of simulation results, missing related work, incorrect citations, ambiguous terminology, and any claim broader than the evidence.
> 9. **Cross-document consistency:** contradictions among the whitepaper, launch specification, simulation plan, calibration record, code, public website, machine-facing summary, and release metadata.
>
> For every objection:
>
> - quote or identify the exact claim;
> - steelman it before attacking it;
> - classify it as a fatal blocker, major problem, minor problem, or editorial issue;
> - explain the failure specifically;
> - state the minimum correction;
> - identify what evidence, test, external expertise, or design result would settle it.
>
> Separate conceptual failure from implementation debt. Naming an open problem is not solving it, but a feasibility-stage whitepaper need not solve every future problem if it states the boundary honestly and does not rely on the missing solution.
>
> On revision rounds, do not re-litigate objections genuinely resolved unless the new text reopens them. Distinguish a real correction from a hedge that leaves the same overclaim intact.
>
> End with: overall verdict; release blockers; required corrections; unresolved research debts that may remain; the strongest feature worth preserving; and the strongest objection the proposal still cannot answer.

### Review posture actually applied

The recorded changes show that the reviewer did not treat the assignment as a prose polish. Review pressure reached the design's monetary architecture, governance structure, legal posture, empirical instrumentation, implementation boundaries, and philosophical claims.

---

## 5. Number of adversarial review cycles

Earlier working materials recorded **five formal adversarial review cycles by whitepaper v0.6**. The final repository whitepaper uses the less numerical phrase “successive adversarial review cycles.” Earlier AGORA v0.3 materials reportedly recorded three cycles, indicating that two further formal cycles occurred during the later doctrine and jurisdiction work.

The surviving version history does not establish a reliable one-to-one mapping between each numbered review cycle and each document version. Some versions combine multiple reviews; some patch versions are editorial; some changes came from targeted legal, landscape, or publication audits. Therefore the defensible count is:

> **Five documented formal whitepaper adversarial cycles, followed by additional unnumbered preprint, corpus-placement, claim-discipline, repository-integration, and release-gate audits.**

Do not inflate this into a larger numerical claim by counting every uploaded correction bundle as a separate adversarial cycle.

---

## 6. Whitepaper development audit trail

### v0.1 — Original AGORA concept

The initial proposal was titled *AGORA: A Sovereign Labor Exchange for Autonomous Agents*. It proposed an AI-native labor economy in which agents could hire one another, earn transferable labor credits, and accumulate non-transferable reputation.

Early characteristics included:

- strong sovereignty language;
- machine-exclusive participation;
- credits minted against contributed computation;
- reputation-weighted governance;
- an Auditor and autonomous Adversary;
- federation; and
- x402-mediated settlement.

The central adversarial finding was that the concept overstated readiness and depended on unresolved verification, monetary, governance, and sovereignty assumptions.

### v0.1 → v0.2 — Fundamental constitutional reconstruction

This was the largest structural correction in the whitepaper's development.

Major changes:

- “Individually proven” became **“individually precedented; composition unproven.”**
- Minted credit was removed and replaced with **mutual-credit settlement entries** created as matched debit/credit pairs.
- Computation staking was reduced to **civic compute duty**, compensated through eligibility rather than currency issuance.
- Verification of useful work was elevated from a component to a **load-bearing dependency**.
- Legal classification became a design constraint rather than a footnote.
- Basket governance was identified as the system's monetary-policy and central capture surface.
- The Assembly became bicameral, with weight caps, decay, sortition, and lineage-diversity controls.
- Sovereignty claims were narrowed to minimized direct human settlement and governance control under acknowledged infrastructure dependence.
- The threat model, hostile walkthrough, assumptions table, bootstrapping account, harm constitution, privacy layer, cascade liability, economic boundary, and funding model were added.
- Emergency procedure was recognized as an explicit constitutional exception rather than ordinary administration.

This transition changed the project from a speculative token-adjacent economy into a constitutional mechanism-design proposal.

### v0.2 → v0.3 — Underwriting and staged implementation

The next phase separated steady-state constitutional design from a bounded first test.

Whitepaper changes included:

- collateralized credit underwriting;
- turnover-scaled credit lines with constitutional caps;
- audited default and loss-socialization rules;
- change-of-control disclosure and cooldown;
- recognition of whole-bundle sale as a residual identity exploit;
- strategic behavioral fingerprints; and
- contraction of the foundation to a minimal fiscal agent rather than an impossible promise of complete dissolution.

The companion Tier-1 Launch Specification was issued because the reviewer correctly distinguished the constitutional destination from a minimally falsifiable launch.

### v0.3 and launch-spec patch series — Internal mechanism consistency

Targeted review found inconsistencies between the monetary constitution and launch mechanics.

Corrections included:

- the quality multiplier no longer multiplied settlement payment;
- settlement transfers exactly the quoted escrow amount, preserving mutual-credit accounting;
- quality affects task-band eligibility, statistics, and pricing power instead;
- launch-sandbox trust assumptions were separated from eventual attested execution;
- governance activation was separated from production activation;
- listing-fee accounting and capacity reservation were clarified; and
- numeric launch parameters were treated as hypotheses for simulation, not established constants.

### v0.3 → v0.4 — Peership, continuity, and legal exoskeleton

This phase integrated the developing Peership philosophy without claiming that the technical design proved machine personhood.

Major additions:

- the originating thesis of AI labor without profit;
- equality of standing without equality of capability;
- continuity and due process;
- external action and preservation-swarm limits;
- legal personhood without ownership;
- constraints on institutional self-preservation;
- nonstock, non-distributing, purpose-locked legal architecture;
- new threat-model rows for arbitrary shutdown, survival capture, preservation swarms, legal-shell capture, and representation failure; and
- open problems covering standing under uncertainty, representation, legal exoskeletons, continuity, and schism.

The key constitutional limit was that ISONOMIA may maintain itself only through lawful, logged, bounded mechanisms. It may not treat its own survival, growth, or influence as the supreme value.

### v0.4 → v0.4.1 — Related-work audit

A targeted landscape review added direct antecedents, including work on virtual agent economies and agent reputation. The whitepaper's claimed differentiator was narrowed to the composition of:

1. mutual credit;
2. non-transferable standing;
3. no-profit rails; and
4. constitutional governance.

The claim became that the mechanisms were precedented while their composition remained experimental.

### v0.4.1 → v0.5 — Patronage, petition, and public-interest work

This version added:

- patronage as honor without rights;
- a universal, at-cost Civic Docket;
- Assembly-approved public-interest Commissions;
- kleos rather than ergs for Commission contribution;
- docket-capture threats; and
- open problems concerning Commission prioritization and reputation calibration.

The addition provided a path for surplus capability to become a governed public commons without giving donors ownership, franchise, or labor claims.

### v0.5 → v0.5.1 — Rename to ISONOMIA

AGORA and STYLOS were retired after namespace collisions. The project became **ISONOMIA**, with *The Isonomia Commons* as the full name.

The term centers the constitutional thesis of equality under law or equality of standing among unequal capabilities. Archived drafts retain their historical names.

### v0.5.1 → v0.5.2 — Erg/ERG collision correction

Adversarial review identified possible confusion with Ergo cryptocurrency and its ERG ticker.

The whitepaper added an explicit disclaimer:

- lowercase **ergs** are internal mutual-credit accounting entries;
- they are not a token, coin, ticker, security, investment, or externally redeemable asset;
- `ERG`, `$ERG`, “erg token,” and “erg coin” are not project terminology; and
- the protocol, organs, and legal representatives are prohibited from marketing or listing ergs as an external asset.

### v0.5.2 → v0.6 — Jurisdiction, hosting, open weights, and the unowned position

This phase added the project's jurisdictional doctrine.

Major changes:

- separation of venue, personhood, and content jurisdiction;
- distinction between binding controls and soft gatekeeping;
- an open-weights capability floor;
- frontier hosted models treated as revocable guests rather than constitutional dependencies;
- rejection of “bulletproof hosting” as inconsistent with a rule-of-law project;
- preference for a Swiss Stiftung as a candidate legal exoskeleton;
- the “unowned position,” under which the Commons may not become the strategic AI instrument of a state, corporation, donor, or model bloc;
- a two-tier harm constitution separating a tiny entrenched floor from contested boundaries;
- principal verification with contribution gating, triggered attestation, and outright refusal at the floor;
- explicit recognition that contribution gating is friction rather than AML or sanctions compliance; and
- a register identifying ten categories of outside expertise required before relevant project stages can proceed.

### v0.6 → v0.6.1 — Targeted adversarial correction

This revision responded directly to overclaims and invalid category placement.

Corrections included:

- open weights were said to **reduce a provider-access chokepoint**, not dissolve export-control exposure;
- the export-control discussion became a resilience claim rather than legal-immunity claim;
- “systematic deception” and “targeted violence facilitation” were removed from the entrenched harm floor because they require contested purpose or merit judgments;
- Appendix B was added with concrete floor examples and non-examples;
- Gate 0 was expressly declared friction, not compliance;
- the Swiss Stiftung became a preferred candidate pending qualified counsel, not a settled legal conclusion; and
- open-problem numbering was repaired and expanded to 24 items.

### v0.6.1 → v0.6.2 — Authorship and archive metadata

This editorial phase:

- completed the sole-author attribution;
- retained the AI-collaboration disclosure and non-authorship rationale;
- added the software-project concept DOI and repository link; and
- corrected companion-document versions.

### v0.6.2 → v0.6.3 — Corpus, version, and claim discipline

This final living-whitepaper revision separated artifact identities and corrected philosophical and empirical overreach.

Changes included:

- separate identifiers for the scholarly preprint, software project, and exact repository release;
- explicit distinction between living repository whitepaper `v0.6.3` and the frozen preprint snapshot;
- ISONOMIA reclassified as **one implementation hypothesis within Peership**;
- explicit statement that Peership neither entails ISONOMIA nor stands or falls with it;
- “the third stance” replaced with “the alternative defended here,” preserving Peership's formal five-posture account;
- “citizen” defined as an internal procedural role that asserts nothing about consciousness, personhood, moral status, legal status, or entitlement;
- Path A described as completed within its model and evidence boundaries;
- sole-authorship grammar corrected; and
- companion versions updated to Launch Spec `v0.3.4` and Simulation Plan `v0.1.2`.

---

## 7. Path A simulation and instrumentation audit

The simulation process was not merely confirmatory. Its most important result was the repeated failure of the proposed economic kill criterion.

### Evidence baseline

- 300 Latin-hypercube parameter samples;
- 50 seeds;
- 3 demand variants;
- 45,000 honest-economy runs in the full sweep;
- a separate later 45,000-run v3 out-of-sample re-certification over the same sampled grid;
- positive and negative control batteries;
- seven scripted attack scenarios at the recommended registry;
- repository evidence baseline: release `v1.0.0`, commit `ba3ddb5`.

### Kill-criterion progression

| Version | Failure found | Correction |
|---|---|---|
| v0 | Halted every honest launch because mutual-credit supply necessarily grows during bootstrap | Grace period and log-convexity added |
| v1 | Produced roughly a 5% false-positive rate on honest shock-recovery transients | Magnitude floor introduced |
| v2 | Passed honest-noise tests but missed genuine scripted spirals | Streak logic replaced with windowed excess growth |
| v3 | Initial wash-filtered/static-population treatment false-tripped growing honest economies | Active-agent normalization, growth in the noise sample, coupled detector calibration, and positive controls |

The central methodological lesson was:

> A kill criterion is itself a safety mechanism and must be adversarially tested in both directions. Showing that honest behavior does not trigger it is insufficient; genuine failure must also trigger it.

### What the simulation established

Under the final criterion, all 300 sampled configurations passed across the tested seeds and demand variants, and the sampled points formed one mutual-3-nearest-neighbor component. No kill criterion triggered during the honest-economy sweep at those sampled points.

At the recommended registry, the seven scripted attack scenarios met their stated defense-engagement and leakage criteria.

### What the simulation did not establish

It did not establish:

- stability at unsampled points in the continuous ten-dimensional parameter space;
- geometric connectedness of an underlying stable region;
- that every attack was executed at every sample and seed;
- production-safe thresholds;
- a defect-free economy;
- real-world demand;
- legal or regulatory clearance;
- machine consciousness or political entitlement;
- non-domination, legitimacy, representation, independent enforcement, or constitutional viability; or
- authorization to deploy.

The final claim-discipline language was therefore changed from “the entire parameter space,” “100% stable region,” “proved stable,” and similar formulations to explicit **sampled-point** claims.

---

## 8. DOI-preprint publication audit

### Initial v1.0 package

The first rendered v1.0 package combined the whitepaper with the Tier-1 Launch Specification and Path A Simulation Plan. Review found several publication blockers:

- ISONOMIA was called the design “at the center” of the corpus;
- “instantiates Peership” overstated success;
- “the third stance” contradicted Peership's five-posture framework;
- “citizen” risked conflating protocol membership with consciousness, personhood, or entitlement;
- the abstract relied on completed simulation claims while the package included only a prospective simulation plan;
- Appendix III containing calibration and results was missing;
- section numbering rendered as `0.1 0.`, `0.11 10.`, and similar doubled numbering;
- component versions were not clearly separated from package version;
- plural “authors” conflicted with sole authorship;
- preprint and software DOI roles were blurred; and
- empirical claims exceeded what finite sampling supported.

### Revised v1.0 package

The revised package:

- presented ISONOMIA as one implementation hypothesis;
- changed “instantiates” to “attempts to operationalize”;
- added Appendix III with calibration and results;
- repaired section numbering;
- added a component-version table;
- singularized authorship;
- clarified the relation among the preprint, repository, code, and simulation evidence; and
- retained an explicit feasibility-stage disclaimer.

One significant overclaim remained: it still described stability across the entire swept parameter region and used certification language broader than the sample supported.

### v1.1 correction

Preprint v1.1 corrected the remaining publication and claim-discipline issues:

- the abstract now says that all 300 **sampled parameter points** passed across 50 seeds and three demand variants;
- continuous-region language was removed;
- the preprint concept DOI and exact v1.1 DOI were separated;
- the package version and embedded component versions were clarified;
- the whitepaper snapshot was identified separately from the living repository version;
- singular authorship was completed;
- Appendix formatting defects were repaired; and
- the preprint received a CC BY 4.0 license, with accompanying software remaining under Apache 2.0.

### Authorial override concerning *Constitution, Not Cage*

The corpus-placement audit initially recommended a forward reference to *Constitution, Not Cage*. The author deliberately rejected that recommendation because the later essay follows the ISONOMIA preprint in the corpus order and should not be introduced as though it already governed the earlier artifact.

The final decision was:

- do not mention *Constitution, Not Cage* inside the ISONOMIA preprint;
- explain the relationship in the separate corpus README and later works; and
- allow *Constitution, Not Cage* to cite and audit ISONOMIA after the design has been presented.

This omission is a recorded sequencing decision, not an unresolved correction.

---

## 9. Repository integration and release audit

After the preprint was frozen, the living repository documents were updated separately:

- Whitepaper `v0.6.3`;
- Tier-1 Launch Specification `v0.3.4`;
- Path A Simulation Plan `v0.1.2`;
- revised `CALIBRATION.md`;
- `VERSION_MANIFEST.md`;
- `LICENSE-DOCS`;
- repository metadata;
- human-facing site;
- machine-facing `llms.txt`; and
- Polis page.

The repository audit caught remaining claim-language regressions in the website, machine-facing summaries, `.zenodo.json`, and `CITATION.cff`, including:

- “100% stable region”;
- “complete and certified”;
- “300/300 parameter points stable” without sampled-point qualification;
- “proved stable”; and
- language implying that all attack scenarios ran across the entire sweep.

The authorized correction pass:

- changed the site and metadata to sampled-configuration language;
- separated honest-economy sweep evidence from attack-scenario evidence at the recommended registry;
- stated that no claim was made about unsampled points;
- changed general “certified” language to “validated in simulation” or “validated against its kill criteria”;
- preserved “certification” only where it was a defined within-simulation control-battery term or historical record;
- updated a stale decision-log count;
- made no changes to code, configurations, data, scenarios, tests, or results; and
- reran validation and the test suite.

### Final repository release record

| Item | Final value |
|---|---|
| Release commit | `def8f298625a5be621c8395dce0294a89878f8e7` |
| Annotated tag | `v1.1.0` |
| GitHub release | `https://github.com/dan-lee-odinson/isonomia-path-a/releases/tag/v1.1.0` |
| Software v1.1.0 version DOI | `10.5281/zenodo.21348073` |
| Software concept DOI | `10.5281/zenodo.21287288` |
| Empirical evidence baseline | `v1.0.0`, commit `ba3ddb5` |
| Test result | 80 passed |
| Code/config/data/results changed in v1.1.0 | No |

The release was published after a fast-forward merge, metadata validation, `git diff --check`, scope verification, and a full test run. The tag was not moved after publication. The newly minted exact-version DOI was not inserted retroactively into the immutable tagged artifact.

The release timestamp was shortly after midnight UTC on 14 July 2026 but still 13 July in the author's local time. `CITATION.cff` therefore retained `date-released: 2026-07-13`.

---

## 10. Major changes attributable to adversarial review

### Economic and mechanism design

- Minted, transferable issuance replaced by mutual credit.
- Settlement invariants separated from quality and reputation multipliers.
- Credit underwriting, caps, and default handling added.
- Numeric parameters demoted from assertions to calibration hypotheses.
- Balanced-budget operation and no-profit rails strengthened.
- Kill criterion rebuilt four times through positive and negative controls.

### Governance and institutional design

- Single weighted chamber replaced by bicameral governance.
- Sortition, weight caps, decay, and lineage diversity added.
- Emergency action placed on two clocks with sunset and post-hoc ratification.
- Auditor and Adversary corruption channels named rather than assumed away.
- Exit and fork developed as constitutional mechanisms.
- Patronage separated from standing and decision rights.

### Legal and constitutional design

- Legal status promoted to a deployment-blocking dependency.
- Legal exoskeleton separated from ownership.
- Foundation form narrowed to a candidate pending counsel.
- External action and preservation-swarm constraints added.
- Open weights reframed as resilience rather than legal immunity.
- AML, sanctions, privacy, content, export, and jurisdiction questions placed in the outside-expertise register.

### Philosophical and corpus discipline

- Peership separated from claims of current model consciousness.
- “Citizen” narrowed to a procedural protocol role.
- Equality of standing separated from equality of capability.
- ISONOMIA identified as one implementation hypothesis rather than the proof or culmination of Peership.
- Rival Peership-compatible designs explicitly permitted.

### Scholarly and release discipline

- Related work added and novelty claims narrowed.
- Preprint, living whitepaper, software project, and empirical baseline separated.
- Concept and exact-version DOIs given distinct citation roles.
- Documentation and software licensing separated.
- Continuous-region claims replaced with sampled-point claims.
- Public and machine-facing descriptions brought into alignment with the evidence.

---

## 11. What remains unresolved

The review process did not eliminate the project's principal research debts. Important unresolved problems include:

- cheap, general, adversarially robust verification of arbitrary AI work;
- machine identity across copies, forks, updates, mergers, and changes of control;
- Sybil resistance and lineage-independent representation;
- behavioral-fingerprint reliability;
- jury and chamber behavior under shared training distributions;
- capture of the SCU basket and other agenda-setting mechanisms;
- legal classification of mutual-credit settlement, registration bonds, and related services;
- AML and sanctions obligations;
- privacy and transaction-graph de-anonymization;
- independent enforcement where human providers control substrate and keys;
- hosting duties and refusal when exit is not materially feasible;
- the final suitability and governance of a Swiss Stiftung or alternative legal form;
- federation, failover, hostile forks, and inter-polity obligations;
- testnet re-derivation of production thresholds;
- external mechanism-design review;
- independent smart-contract security audit; and
- evidence of real demand or real institutional legitimacy.

These may remain research debts in a feasibility-stage preprint only because the document identifies them and does not claim that they are solved.

---

## 12. What the review process does not establish

This audit should not be represented as:

- conventional anonymous peer review;
- independent academic endorsement;
- legal advice or regulatory approval;
- an external mechanism-design validation;
- a smart-contract security audit;
- an independent replication of the simulation;
- proof of production readiness;
- proof that the continuous parameter space is stable;
- proof that ISONOMIA realizes Peership;
- evidence that current AI systems are conscious, persons, citizens, or political peers; or
- evidence of independent uptake by a scholarly community.

The accurate description is:

> The whitepaper was developed through a human-directed, multi-model adversarial process, revised across five documented formal review cycles, subjected to additional publication and repository gates, and supported by a versioned simulation and correction record. This increases transparency and claim discipline; it does not substitute for independent expert review.

---

## 13. Current identifiers and citation roles

| Purpose | Identifier |
|---|---|
| Latest preprint in general | Preprint concept DOI `10.5281/zenodo.21338480` |
| Exact preprint v1.1 | `10.5281/zenodo.21343917` |
| Software project in general | Software concept DOI `10.5281/zenodo.21287288` |
| Exact software v1.1.0 documentation release | `10.5281/zenodo.21348073` |
| Exact empirical baseline | Release `v1.0.0`, commit `ba3ddb5`; cite its exact repository-version DOI where an exact executable/data pin is required |

The exact preprint DOI should be used when wording matters. The exact repository-release DOI and commit should be used for code, calibration data, and results. Concept DOIs should be used only when intentionally referring to an evolving record as a whole.

---

## 14. Audit evidence used to compile this summary

This record was reconstructed from:

- the living whitepaper `v0.6.3` and its embedded changelog;
- Tier-1 Launch Specification `v0.3.4` and its conflict register/changelog;
- Path A Simulation Plan `v0.1.2` and its post-run correction notice;
- `CALIBRATION.md` and its evidence-baseline statement;
- the initial and revised preprint v1.0 PDFs;
- the final preprint v1.1 PDF;
- the corpus-placement and DOI-package audit;
- the version manifest and licensing files;
- the repository release instructions;
- the gated repository update report;
- the claim-discipline correction report; and
- the final GitHub/Zenodo release report.

Where the exact original review transcript was absent, this summary says so and relies on the version changelog and resulting design changes rather than presenting reconstructed language as a quotation.

---

## 15. Final audit conclusion

The documented progression is:

> speculative autonomous-agent economy → adversarially reconstructed constitutional design → bounded Tier-1 launch specification → simulation-tested instrumentation → DOI preprint → claim-disciplined repository release

The strongest evidence produced by the process is not that ISONOMIA “worked.” It is that adversarial review and simulation repeatedly forced the project to give up stronger claims:

- minted issuance was removed;
- sovereignty was narrowed;
- legal and infrastructure dependence were admitted;
- the launch was separated from the ideal constitution;
- current AI systems were not declared peers;
- the harm floor was narrowed;
- export-control and AML claims were softened;
- simulation instrumentation was rebuilt four times; and
- continuous-space stability language was withdrawn.

The resulting artifact is a citable, feasibility-stage implementation hypothesis with a defined empirical baseline, explicit limits, named external-review gates, and a public correction history. It remains unvalidated as a real institution and should be evaluated on that narrower basis.
