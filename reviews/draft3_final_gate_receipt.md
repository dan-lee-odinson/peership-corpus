# *Peership* Draft 3 ZIP — Receipt and Final-Gate Result

**Review date:** 14 July 2026  
**Authoritative input:** `Peership_draft3_review_package.zip`  
**ZIP SHA-256:** `8e9cc97b8e8f70199bbd2fd290f2a0884882908741fd2e4c77a3ad0042161d50`

## Verdict

**The ZIP is genuine Draft 3, transferred intact. It is not Draft 2.** Its internal manifest matches all five substantive files, and the canonical paper ends with the complete Walzer 1977 entry. The Draft 1 truncation objection and any Draft 2 receipt objection are inapplicable.

**The final publication gate nevertheless remains CONDITIONAL rather than PASS.** The distinction is temporal: this ZIP contains the Draft 3 that repaired the Draft 2 re-review gate, but it is byte-for-byte identical to the Draft 3 subsequently examined in `PEERSHIP_DRAFT3_GATE_CONFIRMATION_REVIEW_v1.0.md`. It therefore does not yet contain the five narrower corrections identified by that later gate-confirmation review.

Both propositions are true:

1. the package contains the correct Draft 3 and the major Draft 2 repairs; and
2. the package predates the five post-Draft-3 gate-confirmation corrections.

No foundational objection is reopened. This is a version-order and final-edit issue, not a failed argument or failed transfer.

## Receipt verification

| File | Bytes | SHA-256 | Result |
|---|---:|---|---|
| `Lee-Odinson_2026_Peership-Thesis_v1.0_draft3.md` | 80,776 | `1df15d7d8bc7b20a7e3fd0d9c85fa939130509ba63b0ed232d7233fc119be9a3` | Correct Draft 3; complete |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0_draft3.md` | 4,442 | `f98dfa03b87f874a26fa83d6bf6f05d9108390edbb3bf10ea9d65a819653650a` | Correct Draft 3 companion |
| `Lee-Odinson_2026_Peership-Theses_One-Pager_v1.0_draft3_render-check.pdf` | 117,059 | `3aa3dc3f46a07790b853e439f8402f24d23311766f1d081e51b6eebb997f9b95` | One US-Letter page; complete |
| `Peership-Thesis_draft3_GATE_DISPOSITIONS.md` | 4,771 | `5083dcc6ca478b2a01e3668bce4c755da3cfabbb7d207d22e36ce59219776c7f` | Correct Draft 3 dispositions |
| `Peership_apparatus_additions_PENDING.md` | 9,412 | `a8ff50b696ca834b3e558b3e79b8456f0cfe3cfbdf2c291e1559e3f05d948c9d` | Correct Draft 3 pending apparatus |

`sha256sum -c MANIFEST_draft3.txt` returns **OK** for all five files. Its warning about two improperly formatted lines concerns the human-readable title and date at the top of the manifest, not a checksum mismatch. For a machine-clean manifest, prefix those lines with `#` or move them to a separate README.

## Five corrections still absent

### 1. Conform §9's aggregation language

The paper still says:

> “a consequential route through amendment **or** accountable representation”

That conflicts with §§2–3, which require both amendment access and accountability/direct participation at the deciding stage. It also still asks rival designs to “accept these seven properties” (§9) and “accept the seven properties of §9” (§13), even though exit and fork have just been reclassified as safeguards admitting functional substitutes.

Use:

> Publicity, due process, independent enforcement, and a consequential rule-formation route satisfying both amendment access and accountable representation or direct participation are constitutive functions of full peership.

Then change the rival-design invitations to require the constitutive functions plus credible anti-entrenchment safeguards, including functional substitutes where exit or fork is omitted.

### 2. Correct *How to Count AIs* author order

The package still gives **Arbel, Goldstein, Salib** in the prose, paper reference, dispositions, and pending BibTeX. The current arXiv record gives **Yonathan Arbel, Peter Salib, Simon Goldstein**: <https://arxiv.org/abs/2603.10028>.

Correct the prose in §§5 and 11.2, the reference, `arbel2026counting`, and the metadata claim in the dispositions file.

### 3. Fix the two canonical-section pointers in the pending apparatus

The pending apparatus introduction correctly says the two adjacent-field sources appear in canonical §5, but both new BibTeX notes still say *The Peership Thesis* **§4**. Change those two notes to **§5**. Sourcebook **§4.3** remains correct and should not be changed.

### 4. Narrow the remaining fork-scan description

Section 9 still says:

> “In the comparative scan recorded in the apparatus…”

The supplied apparatus records the reviewed constitutional and emigration instruments but not a reproducible comparative-search protocol. Use:

> Among the constitutional secession clauses and emigration-rights instruments reviewed in the apparatus, no implemented analogue of executable, unconfiscated fork was identified; the claim is limited to those materials.

Alternatively, archive the full comparative protocol and result set before retaining stronger scan language.

### 5. Repair the rendered DOI

The PDF is genuinely one page and visually complete, but the footer still renders and extracts the first DOI as:

> `10.5281/zen-odo.21313987`

Prevent line breaking inside the DOI, rerender, and confirm that displayed text, copied text, and the hyperlink all preserve `10.5281/zenodo.21313987` exactly.

## Release decision

**Do not request another full hostile review.** Apply the five edits above, complete the already acknowledged deposit-day apparatus/DOI tasks, generate a new manifest, and perform one mechanical comparison against this receipt. The corrected package can then receive **PASS / RELEASE-READY**.

For the next ZIP, changing the version marker or adding a short `POST_GATE_CHANGES.md` would prevent the major Draft 3 repair set from being confused with the later gate-confirmation patch set.
