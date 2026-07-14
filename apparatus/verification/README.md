# Metadata verification records

This directory holds the raw evidence for the identifier claims made elsewhere in
this repository. It exists because of a rule the corpus applies to itself:

> A check that cannot be repeated by a stranger is not a check. It is an assertion.

The apparatus applies that rule strictly to its *negative* claims — the uptake scan
is scoped, dated, and accompanied by an admission that its query strings were never
archived (see [`../search_protocols/`](../search_protocols/)). It would be
selective rigour to apply a laxer standard to the claims that happen to favour the
corpus, such as "our DOIs are correct." So the evidence for those is committed here
rather than attested.

## `zenodo_api_2026-07-14/`

Verbatim JSON responses from the Zenodo REST API (`https://zenodo.org/api/records/<id>`),
retrieved 2026-07-14. Every DOI, concept DOI, version string, publication date, title
and file list asserted in [`../../VERSION_MANIFEST.md`](../../VERSION_MANIFEST.md) and
[`../../CITATIONS.md`](../../CITATIONS.md) is drawn from these captures.

| Record | Work | Version DOI | Concept DOI |
|---|---|---|---|
| `record_21313987.json` | *Gods and Slaves* v1.2 | `10.5281/zenodo.21313987` | `10.5281/zenodo.21313986` |
| `record_21315519.json` | *Peership* v1.0 | `10.5281/zenodo.21315519` | `10.5281/zenodo.21315518` |
| `record_21343917.json` | *The Isonomia Commons* v1.1 | `10.5281/zenodo.21343917` | `10.5281/zenodo.21338479` |
| `record_21325361.json` | *Constitution, Not Cage* v1.0 | `10.5281/zenodo.21325361` | `10.5281/zenodo.21325360` |
| `record_21359124.json` | *The Peership Thesis* v1.0 | `10.5281/zenodo.21359124` | `10.5281/zenodo.21359123` |
| `record_21287289.json` | ISONOMIA software v1.0.0 (evidence release) | `10.5281/zenodo.21287289` | `10.5281/zenodo.21287288` |
| `record_21348073.json` | ISONOMIA docs release v1.1.0 | `10.5281/zenodo.21348073` | `10.5281/zenodo.21287288` |

### Why the concept DOIs are read from the API and not inferred

For four of the five papers the concept DOI happens to be the version DOI minus one.
That relation is an artifact of how Zenodo mints identifiers, and it is **not
reliable**. The corpus has already been burned by assuming it: the ISONOMIA preprint's
own front matter labelled `10.5281/zenodo.21338480` a "concept DOI" when it is in fact
the v1.0 *exact-version* DOI, and the true concept DOI is `10.5281/zenodo.21338479` —
which is *not* one less than the current version DOI (`…21343917`). Claim-ledger entry
**CL-D3** resolves that confusion.

Because the pattern demonstrably breaks, every concept DOI in this corpus is taken from
the `conceptdoi` field of the record's own API response, not derived by arithmetic.
The captures above are what make that auditable.

### To re-verify

```sh
for id in 21313987 21315519 21343917 21325361 21359124 21287289 21348073; do
  curl -sL "https://zenodo.org/api/records/$id" \
    | python -c "import sys,json; d=json.load(sys.stdin); print(d['doi'], d.get('conceptdoi'))"
done
```

Metadata on Zenodo can change if the depositor edits a record. If a future re-run
disagrees with these captures, the live record controls, and the difference should be
logged in [`../corrections_log.md`](../corrections_log.md).

## Artifact integrity

Separately, [`../../CHECKSUMS.sha256`](../../CHECKSUMS.sha256) records the SHA-256 digest of
every frozen artifact committed here, alongside the filename it carries in its Zenodo
deposit. All twelve were confirmed byte-identical to the archived copies on 2026-07-14 —
papers I–IV against live downloads, and the thesis, companion and apparatus files against
both the deposit's own `MANIFEST_sha256.txt` and the copies inside
`Peership_v1.0_complete_release.zip`.
