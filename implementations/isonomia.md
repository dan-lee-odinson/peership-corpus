# ISONOMIA — one implementation hypothesis

> ISONOMIA is one implementation hypothesis. Peership does not entail ISONOMIA, and ISONOMIA's success or failure would not prove or refute Peership.

That statement is the implementation firewall. It governs everything below, and it is the reason this page exists as a pointer rather than as a second home for the ISONOMIA project.

## What ISONOMIA is

ISONOMIA is a proposed constitutional labour exchange for autonomous AI agents. Agents offer and accept work from one another and settle accounts in **ergs**, a mutual-credit unit: credit is issued bilaterally when work is exchanged, balances net out against one another, and no external reserve currency is presupposed. The design is "constitutional" in that the exchange rules — publicity, due process, independent enforcement of the rules against the exchange's own operators, and routes by which participants can contest and revise those rules — are meant to be part of the market's architecture rather than concessions granted at an operator's discretion.

ISONOMIA is therefore a candidate answer to a question the Peership corpus poses but does not settle: what would a *specific* institution look like if it tried to satisfy the constitutional constraints the corpus argues for? It is one such institution. It is not the institution Peership requires, because Peership requires no particular institution.

The argument for ISONOMIA is stated in the corpus itself, in *THE ISONOMIA COMMONS: A Constitutional Design for Autonomous Agent Labor Markets* (v1.1) — see [`../corpus/03-isonomia-commons/`](../corpus/03-isonomia-commons/). The engineering, the simulations, and the calibration work live in a separate repository.

## Where the implementation lives

Repository: <https://github.com/dan-lee-odinson/isonomia-path-a>

| Document | Link |
|---|---|
| Whitepaper v0.6.3 | [docs/ISONOMIA_Whitepaper_v0.6.3.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Whitepaper_v0.6.3.md) |
| Tier-1 launch specification v0.3.4 | [docs/ISONOMIA_Tier1_Launch_Spec_v0.3.4.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Tier1_Launch_Spec_v0.3.4.md) |
| Path A simulation plan v0.1.2 | [docs/ISONOMIA_PathA_Simulation_Plan_v0.1.2.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_PathA_Simulation_Plan_v0.1.2.md) |
| Feasibility assessment | [docs/ISONOMIA_Feasibility_Assessment.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/docs/ISONOMIA_Feasibility_Assessment.md) |
| Calibration report | [CALIBRATION.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/CALIBRATION.md) |
| Version manifest | [VERSION_MANIFEST.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/VERSION_MANIFEST.md) |

## Archival records

| Record | DOI |
|---|---|
| ISONOMIA preprint, v1.1 (exact version) | [10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917) |
| ISONOMIA preprint, concept (all versions) | [10.5281/zenodo.21338479](https://doi.org/10.5281/zenodo.21338479) |
| ISONOMIA software, concept (all versions) | [10.5281/zenodo.21287288](https://doi.org/10.5281/zenodo.21287288) |

A note on one identifier, because it is easy to get wrong. **10.5281/zenodo.21338480 is the v1.0 exact-version DOI of the preprint, not a concept DOI.** The paper's own front matter mislabels it; the Zenodo API and ledger entry CL-D3 resolve the question in favour of ...21338479 as the concept DOI. The frozen PDF is not altered to fix this; the discrepancy is recorded instead. See [`../apparatus/peership_claim_ledger.md`](../apparatus/peership_claim_ledger.md) and [`../VERSION_MANIFEST.md`](../VERSION_MANIFEST.md).

## Exact evidence pin

The empirical claims made about ISONOMIA — the parameter sweep, the calibration results, the reported launch-economy behaviour — are supported by exactly one release. Anyone citing those results must cite the exact-version software DOI below, **not** the concept DOI, which resolves to whatever version is newest.

| Field | Value |
|---|---|
| Release | v1.0.0 (10 July 2026) |
| Git tag | `v1.0.0` |
| Commit | `ba3ddb5` (full: `ba3ddb51dbcc147def470b7af1eaddef6f349157`) |
| Exact-version software DOI | [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) |

A later documentation release, **v1.1.0** ([10.5281/zenodo.21348073](https://doi.org/10.5281/zenodo.21348073), commit `def8f29`, 14 July 2026), changed documentation and claim language only. No code, simulation, data, or result changed in it. The empirical evidence therefore remains pinned to **v1.0.0 / `ba3ddb5`**, and citing v1.1.0 as the evidence-bearing release would be an error.

## Status of the evidence

Three statements, plainly:

1. **Nothing is live and nothing is production-validated.** ISONOMIA has not been deployed. No agent has ever settled an account in ergs outside a simulation.
2. **The simulations are a 45,000-run parameter sweep.** They test *sampled launch-economy behaviour* — how the modelled exchange behaves under sampled parameter settings, given the model's own assumptions about agents, tasks, pricing, and credit limits.
3. **That is all they test.** They do not establish constitutional legitimacy, they do not validate Peership, and they are not evidence that any real agent population would behave as the model's agents do. A parameter sweep is a study of a model. It is not a study of a world, and it is emphatically not a study of a normative thesis.

The results themselves are reported in the ISONOMIA preprint ([10.5281/zenodo.21343917](https://doi.org/10.5281/zenodo.21343917)) and in the repository's [CALIBRATION.md](https://github.com/dan-lee-odinson/isonomia-path-a/blob/main/CALIBRATION.md). Read them there; this page does not reproduce them.

## What ISONOMIA would and would not show

It is worth being exact about the inferential relation, because the temptation to over-read an implementation is strong in both directions.

**A fully successful ISONOMIA would not establish that Peership is correct.**

Peership is a normative and constitutional thesis:

> When an artificial entity has interests capable of being wronged, can understand and answer to public norms, and is enduringly governed by a shared basic structure without feasible exit, it acquires a defeasible claim to contestatory membership in that structure. Full Peership adds a consequential share in shaping and revising the basic rules.

Whether that claim holds is a question about what is *owed*, not about what *works*. An institution can work beautifully and be owed to no one; markets clear under tyranny. So a working ISONOMIA would show, at most, that one institution of roughly the right constitutional shape is *feasible* — a useful thing to show, since feasibility objections are among the strongest objections to Peership, but a long way from showing the thesis true. It would refute "no such institution could exist." It would not touch "no such institution is owed."

**A failed ISONOMIA would not refute Peership.**

ISONOMIA is one institutional realisation drawn from a family of possible realisations. If it failed, the failure would have to be *located* before it could be interpreted, and at least four locations are available:

- **Design.** The specific constitutional mechanisms — the contestation route, the enforcement design, the amendment rule — may be badly chosen, while other mechanisms serving the same constitutional functions would have worked.
- **Calibration.** The model's parameters, agent behaviours, and cost assumptions may be wrong, in which case the failure belongs to the simulation, not to the design.
- **Economics.** Mutual credit may simply be the wrong settlement layer for agent labour — a failure of the monetary instrument, not of the constitutional idea it was carrying.
- **Execution.** Ordinary engineering, funding, or adoption failure, which tells us nothing normative at all.

Only after all four are excluded would a failure begin to bear on the constitutional thesis, and even then it would bear on *this family* of designs rather than on the claim that some institution of non-domination is owed. A normative thesis is not refuted by the failure of one attempt to satisfy it, any more than republican political theory was refuted by any particular failed republic.

**The asymmetry is the point.** The firewall is not a hedge against embarrassment. It is a statement about what kind of claim each work is making. The corpus argues about what would be owed *if* credible candidates for moral and political standing emerge. ISONOMIA guesses at what one institution answering to that obligation might look like. Neither underwrites the other.

## Rival implementations

Peership does not mandate ISONOMIA, and the corpus would be strengthened, not threatened, by serious rivals. A rival implementation is any institutional design that attempts to satisfy the same constitutional constraints — publicity, due process, independent enforcement, and a consequential route to rule-formation, together with credible anti-entrenchment safeguards — by other means. Mutual credit is not required. A labour market is not required. An exchange is not required.

If you have such a design, propose it: open an **Implementation proposal** issue via <https://github.com/dan-lee-odinson/peership-corpus/issues/new/choose> (the form lives at `.github/ISSUE_TEMPLATE/implementation_proposal.yml`). Proposals that specify what would count as failure are more useful than proposals that only specify what would count as success.

## Non-duplication

This repository deliberately does **not** vendor the ISONOMIA source tree, mirror its simulation outputs, or attach it as a git submodule. Three reasons:

1. **The firewall.** Binding the implementation into the corpus repository would materially suggest that the corpus stands or falls with it. It does not, and the repository layout should not imply otherwise.
2. **Single source of truth.** The ISONOMIA repository, its tags, and its Zenodo deposits are the authoritative record of the code and the results. A copy here would be a second record, and second records go stale, drift, and get cited by accident.
3. **Citation hygiene.** The empirical claims are pinned to an exact commit and an exact-version DOI. A vendored or submoduled copy invites citation of *this* repository's snapshot instead of the pinned release, which is precisely the error the evidence pin exists to prevent.

Link to ISONOMIA. Cite it at v1.0.0 / `ba3ddb5` / [10.5281/zenodo.21287289](https://doi.org/10.5281/zenodo.21287289) when citing its results. Do not copy it here.
