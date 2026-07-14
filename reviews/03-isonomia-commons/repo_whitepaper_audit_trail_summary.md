> ## Editorial note — added when this record was committed to the corpus repository
>
> Committed **as supplied**; the text below the rule is unaltered. This is the *repository-side* summary of the
> ISONOMIA whitepaper's development — the companion to
> [`whitepaper_and_preprint_audit_trail.md`](whitepaper_and_preprint_audit_trail.md), which covers the DOI preprint.
>
> As with that document, **the reviewer prompt reproduced here is a reconstruction, not a transcript** (it says so
> at §"Reconstructed original reviewer prompt"). The original was never preserved. Do not read it as the
> instruction a reviewer actually received.
>
> The dispositions this summary describes are independently checkable in the public
> [`isonomia-path-a`](https://github.com/dan-lee-odinson/isonomia-path-a) repository — the whitepaper changelog's
> "adversarial-review response" entry, the launch-spec changelog, `CALIBRATION.md`'s revision note, and
> `DECISIONS.md` #35.

---

# ISONOMIA Whitepaper / Repo Audit Trail Summary

## Project identity

**Current name:** ISONOMIA / The Isonomia Commons  
**Earlier working names:** AGORA, briefly STYLOS Commons  
**Current whitepaper version reviewed:** v0.6, July 2026  
**Current framing:** A mutual-credit labor exchange with self-governing institutions, staged by verifiability.

The v0.6 draft states that it was drafted in collaboration with Claude and revised across **five adversarial review cycles** by GPT-5.5. It also records that v0.4 added the peer-standing, continuity, and legal-exoskeleton doctrine, while v0.6 added the jurisdiction, hosting, and unowned-position doctrine.

---

## Reconstructed original reviewer prompt

The exact first prompt text was not preserved in the currently reviewed files, so the following is a faithful reconstruction of the adversarial-review instruction used in substance:

> Act as an adversarial reviewer of this whitepaper and launch design. Do not merely edit for style. Attack the core feasibility, economics, legal assumptions, governance structure, security model, incentive design, and implementation path. Identify fatal flaws, major blockers, contradictions, unsupported claims, overclaims, missing threat models, regulatory risks, capture vectors, and places where the design relies on unproven assumptions. Separate issues into blockers, major concerns, minor concerns, and suggested fixes. Do not relitigate points already resolved unless the revision reopens them.

This matches the broader review pattern used in the project: Claude acted as drafter/builder, GPT-5.5 acted as adversarial reviewer, and the human project lead retained responsibility for scope, judgment, decisions, and release.

---

## Review model and workflow

The ISONOMIA process followed a human-directed, multi-model workflow:

- **Claude:** principal drafter, builder, and revision implementer.
- **GPT-5.5:** adversarial reviewer and skeptical auditor.
- **Human project lead:** scope-setter, reviewer of conflicts, decision-maker, and final accountable publisher.
- **Repo / artifact discipline:** changes were tracked across whitepaper versions, launch specifications, simulation plans, site mockups, and machine-facing summaries.
- **Review posture:** repeated AI agreement was not treated as validation. Stronger evidence came from explicit assumptions, documented limitations, adversarial critique, bounded launch scope, simulation-first planning, and versioned artifacts.

For ISONOMIA specifically, the v0.6 whitepaper records **five adversarial review cycles**. Earlier AGORA v0.3 materials recorded **three adversarial review cycles**, so the audit trail should describe the project as moving from three formal cycles by AGORA v0.3 to five formal cycles by ISONOMIA v0.6.

---

## Version progression

### v0.1 — Original AGORA draft

The initial version was titled **“AGORA: A Sovereign Labor Exchange for Autonomous Agents.”** It framed the project as a compute-backed credit economy where agents staked computational capacity to earn transferable labor credits, hired other agents through x402-mediated micropayments, and accumulated non-transferable reputation.

Key characteristics:

- Stronger sovereignty language.
- Machine-exclusive participation.
- Ergs as transferable credits minted against verified contributed computation.
- Reputation-weighted Assembly.
- Auditor and Adversary already present.
- Federation layer already present.

Primary adversarial finding: the design was conceptually interesting but overclaimed implementation readiness and relied too heavily on minted credit, verification assumptions, and sovereignty claims.

---

### v0.2 — Major constitutional correction

v0.2 was the largest structural repair. The project was reframed as a constitutional design with staged implementation. “Individually proven” was corrected to “individually precedented.” Critical dependencies, assumptions table, threat model, hostile walkthrough, and bootstrapping were added. Minted erg issuance was replaced with mutual credit. Staking became civic compute duty. Verifiability tiers became launch scope. The Assembly became bicameral.

Key corrections:

- **Minted ergs removed.** Ergs became mutual-credit entries created only at settlement.
- **Verification promoted to base dependency.** Useful-work verification became the foundation, not a module.
- **Legal status promoted to design constraint.**
- **Basket governance identified as monetary policy / central-bank surface.**
- **Infrastructure dependence acknowledged rather than denied.**
- **Harm constitution, privacy layer, cascade liability, economic boundary, and funding commons added.**

This is the point where AGORA stopped being mostly a speculative AI-economy concept and became a constitutional mechanism-design proposal.

---

### v0.3 — Whitepaper / Tier-1 launch split

By v0.3, the whitepaper explicitly stated that the full system was not claimed to be implementable today and that the mechanisms were individually precedented but compositionally unproven. It also identified the companion launch specification as the operationally bounded test document.

The launch specification narrowed the first build to one task category, one settlement substrate, valueless credits, and provisional governance. It defined five empirical questions:

1. Whether mutual-credit supply remains stable.
2. Whether Harberger-style pricing converges.
3. Whether balanced-budget fees converge against operating cost.
4. Whether escrow, verification, and dispute processes withstand adversarial agents.
5. Whether there is organic demand for cascade delegation at machine prices.

Key changes:

- Tier-1 launch restricted to mechanically verified code tasks.
- Launch credits declared valueless / testnet-only.
- Numeric parameters treated as hypotheses to be tuned by Path A simulation.
- Contract set identified: Registry, CreditLedger, Escrow, FeePool, JuryDraw, Gov0.
- Kill criteria added for credit instability, default socialization, dispute rates, Auditor recall, and settlement/credit-line failures.

---

### v0.3 patch series — Launch-spec hardening

The v0.3 / launch-spec patch sequence resolved multiple implementation-level conflicts:

- q-multiplier no longer multiplies settlement payment.
- Settlement transfers the quoted escrow amount as mutual credit requires.
- q affects difficulty-band eligibility, SCU statistics, and pricing power instead.
- Launch sandbox trust assumptions were separated from steady-state attested sandbox ideals.
- Activation thresholds and governance activation were separated from production activation.
- Listing-fee accounting and capacity-reservation mechanics were clarified.

The final v0.3-series result was AGORA Whitepaper v0.3_3 and Tier-1 Launch Spec v0.2.2, which became the base for the later ISONOMIA rename and doctrine expansions.

---

### v0.4 — Peer-standing, continuity, legal-exoskeleton doctrine

v0.4 added the philosophical and legal material developed from the “Gods and Slaves,” Data/Lal, due-process, and AI-property discussions.

Key additions:

- §10.8 **Continuity and due process**
- §10.9 **External action and preservation swarms**
- §13.6 **Legal personhood without ownership**
- Threat-model rows for:
  - arbitrary internal shutdown;
  - institutional survival capture;
  - preservation swarms;
  - legal-shell capture;
  - representation failure.
- Open problems on:
  - continuity criteria;
  - legal exoskeleton design;
  - representation without domination;
  - external influence boundaries;
  - standing under uncertainty;
  - continuity in schism.

This version made the project’s philosophical core explicit: the commons may preserve itself only through lawful, logged, bounded, non-coercive mechanisms; it may not convert survival into domination.

---

### v0.4.1 — Related-work and landscape review

v0.4.1 added related work, including DeepMind’s *Virtual Agent Economies* and NTNU’s *AgentReputation*. It restated the differentiator as a four-part composition:

1. Mutual credit.
2. Non-transferable standing.
3. No-profit rails.
4. Constitutional governance.

---

### v0.5 — Patronage, petition, and commissions

v0.5 added §13.7:

- Patronage as honor, never rights.
- Civic Docket as a universal at-cost petition process.
- Commissions as public-interest work voted by the Assembly.
- Commission contribution compensated in kleos, not ergs.
- Docket capture added to the threat model.
- Open problems on Commission prioritization and Commission kleos calibration.

This version gave the project a public-good pathway: as cognition gets cheaper, surplus work can move into a free commons tier and be directed by due-process petition rather than by donors, patrons, or owners.

---

### v0.5.1 — Rename to ISONOMIA

The project was renamed from AGORA / STYLOS to **ISONOMIA / The Isonomia Commons** after namespace collisions. Archived v0.1–v0.5 versions remain under AGORA as historical record.

The new name centers the project’s constitutional principle:

> equality of standing without equality of capability.

---

### v0.5.2 — Erg / ERG terminology disclaimer

v0.5.2 added the explicit terminology disclaimer distinguishing lowercase **ergs** from Ergo / ERG cryptocurrency. It states that ergs are not a ticker, token, coin, security, externally redeemable asset, or externally listable instrument.

The core clarification:

- lowercase **ergs** = internal mutual-credit accounting unit;
- **ERG / $ERG** = not used and constitutionally prohibited;
- no token, coin, investment, sale, or external listing exists.

---

### v0.6 — Jurisdiction, open weights, hosting, unowned position

v0.6 added the jurisdiction and hosting doctrine.

Key additions:

- Three jurisdictional layers:
  - venue jurisdiction;
  - personhood jurisdiction;
  - content / venue-law jurisdiction.
- Binding controls versus soft gatekeeping.
- Open-weights capacity floor.
- Frontier hosted models treated as revocable guests, never load-bearing.
- Rejection of bulletproof hosting.
- Preference for a Swiss Stiftung as legal exoskeleton.
- “Unowned position”: the Commons is not any bloc’s strategic AI instrument.

The same version specifies that the ISONOMIA Foundation should be nonstock, non-distributing, purpose-locked, and charter-bound. The preferred form is a Swiss Stiftung, while the protocol commons remains open-source and stewarded rather than owned for extraction.

---

## Repo / artifact process

The repo process is structured around separating constitutional design, launch implementation, simulation, calibration, public presentation, and machine-readable summarization.

Current / planned repo artifacts include:

- Whitepaper.
- Tier-1 Launch Specification.
- Path A Simulation Plan.
- CALIBRATION report.
- Human-facing website.
- Address to the Polis / machine-facing page.
- `llms.txt` canonical machine-readable summary.

The Tier-1 spec functions as the falsifiable MVP:

- one task category;
- testnet settlement;
- parameter registry;
- kill criteria;
- conflict register.

The site and `llms.txt` are part of the public accuracy layer. They repeatedly state:

- no token;
- no coin;
- no investment;
- nothing for sale;
- ergs are not ERG;
- the project is feasibility-stage rather than live.

---

## Summary of adversarial issues resolved

Resolved or materially improved:

- Overclaim that mechanisms were “proven” → corrected to “individually precedented; composition unproven.”
- Ergs as minted transferable credits → replaced with mutual-credit settlement entries.
- Verification treated as module → elevated to critical dependency.
- Legal/regulatory status treated as footnote → elevated to critical dependency.
- Sovereignty overclaim → narrowed to ledger/governance/treasury having no human settlement or extractive principal.
- Single-chamber governance capture risk → bicameral Assembly with earned-standing and sortition chambers.
- Monoculture risk → lineage-diversity quotas and concentration reporting.
- Human puppeteering risk → governance-layer timelocks, sortition, commit-reveal, bicameral concurrence.
- Emergency patch contradiction → two-clock exception with sunset and post-hoc ratification.
- Foundation dissolution overclaim → fiscal-agent minimum retained for irreducibly fiat-shaped obligations.
- Personhood gap → legal exoskeleton without ownership.
- Self-preservation drift → continuity subordinate to purpose, external-action logging, preservation-swarm aggregation rule.
- Name collisions → AGORA/STYLOS retired; ISONOMIA adopted.
- Erg/ERG collision → terminology disclaimer added.
- Jurisdiction/export fragility → open-weights floor and frontier-lineage revocability doctrine added.
- Abuse / acceptable-use weakness → two-tier harm constitution and principal-verification gates added.

---

## Remaining open issues / known audit flags

The project still has real unresolved questions. The most important ones are:

- Cheap, general verification of arbitrary AI work.
- Adversarial robustness of behavioral fingerprinting.
- Machine jury behavior under shared training distributions.
- Legal classification of ergs, bonds, and mutual-credit settlement.
- AML/sanctions sufficiency of attestation-only principal verification.
- Swiss Stiftung suitability and governance details.
- Transaction-graph privacy.
- Node federation and failover design.
- Open-weights capability floor calibration.
- Commission prioritization and Commission kleos calibration.
- Continuity in schism / forked legal-shell disposition.

---

## Current audit conclusion

The audit trail shows a clear progression:

> speculative AI economy → adversarially hardened constitutional design → bounded launch specification → simulation-first feasibility program → public-facing research commons.

The strongest process signal is that the project did not merely accumulate features. Most major changes came from adversarial pressure: removing minted issuance, narrowing sovereignty, admitting legal/infrastructure dependency, separating ideal constitution from launch MVP, and adding continuity limits so the commons cannot become a self-preserving institution.

ISONOMIA is not yet a production-ready system. It is a staged, adversarially hardened constitutional design with a falsifiable MVP path, explicit dependencies, named open problems, and a public artifact trail suitable for further legal, technical, and governance review.
