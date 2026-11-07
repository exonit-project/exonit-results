> **Notice: contributions paused.** These results are being recomputed with a revised pipeline. Pull requests and issues are paused until the next release.

# ExoNit — public results

> **Experimental — personal research project (Confidence Level L0).** Results are not validated by an
> astrophysicist. These are raw pipeline outputs. **Do NOT submit anything here to ExoFOP** and do not make
> scientific claims based on it. See [CONFIDENCE_LEDGER.md](CONFIDENCE_LEDGER.md).

Generated 2026-11-07T09:00:28Z from internal commit `a32c4e0fd6c03807cd1ad45486cbdccd3ebb986c` by `scripts/release/build_public_results.py`
of [exonit-public](https://github.com/marc252/exonit-public). Everything here is generated; do not edit by hand.

**Recompute progress:** 8 of 924 strong rows recomputed with the v3 FPP model; the others read `pending recompute`.

Note: membership of the strong and finalist lists was decided with the previous FPP model and is being recomputed.

The values withdrawn from this repository remain in its git history.

False-positive probabilities (FPP) are published only when they come from model v3; every other FPP, and every
label derived from it, reads `pending recompute`. Sections that could not be rewritten safely are not published
(`withheld_sections` in `INDEX.json`).

## What is here
- `sectors/s<NNNN>/summary.md` — one row per processed lot (TICs completed, failed, strong candidates, finalists).
- `sectors/s<NNNN>/lots/<run_id>.json` — the lot scorecard (recall vs the TOI catalog by depth/period/sectors,
  period/depth/duration precision, false-positive rates per stage). `<run_id>_dossier.md` — the vetting dossier
  (strong candidates after the systematic-family veto, finalists, shared-signal cross-check, cross-sector queue).
- `candidates/strong_candidates.csv` — every strong-candidate row from every dossier, with its `pipeline_label`
  and the catalog cross-match columns.
- `candidates/new_candidates.csv` — only the rows found in none of the catalogs;
  `candidates/crossmatch_sources.json` — exactly which catalogs, versions and retrieval time were used.
- `benchmarks/` — not published for now: its L2/L3 recall figures depend on the former FPP values.
- `INDEX.json` — machine-readable totals.

## How to read `pipeline_label`
The label is a raw pipeline output. **None of these labels is a disposition, a validation or a confirmation:** no
follow-up observations (spectroscopy, high-resolution imaging, ground-based photometry) were used for any of them.

| pipeline_label | what it means |
|---|---|
| `tri_low_fpp` | TRICERATOPS false-positive probability FPP < 0.015 and nearby-FPP < 0.001. These are the thresholds of Giacalone et al. (2021) for statistical validation, but here they are computed from the TESS light curve alone, **without the follow-up constraints that validation requires**, so this is not a validation. |
| `tri_mid_fpp` | TRICERATOPS FPP below 0.5 but not meeting the `tri_low_fpp` thresholds. |
| `tri_high_fpp` | TRICERATOPS FPP >= 0.5: likely a false positive. |
| `tri_failed` | The TRICERATOPS run failed (no FPP). |
| `pending recompute` | The FPP of this row has not been recomputed with model v3 yet; no FPP and no FPP-derived label is shown. |
| `unscored` | No TRICERATOPS result was available when the dossier was written. |
| `clf_planet_candidate` | The gradient-boosted verdict classifier scored above its threshold on the pipeline's own features. A classifier score is not a disposition. |

Older dossiers wrote the first three TRICERATOPS labels with different words; the published files use the names
above so that nobody reads them as a validation.

## Known objects and aliases
Every strong row is cross-matched (by TIC, or by sky position for the Gaia tables) against: the ExoFOP TOI and
CTOI lists, the NASA Exoplanet Archive confirmed planets, the TESS EB catalog (Prsa et al. 2022), the TESS Ten
Thousand EB catalog (Kostov et al. 2025) and the Gaia DR3 eclipsing-binary and non-single-star orbital tables.

- `known_status` (first match wins): `known_planet` (confirmed in the archive or TFOPWG CP/KP) > `known_fp`
  (TFOPWG FP/FA) > `toi_candidate` (a TOI: TFOPWG PC/APC or not yet dispositioned) > `ctoi` > `known_eb` (any EB or
  spectroscopic-binary catalog) > `new` (in none of them).
- `known_ids`, `catalog_period_days`: the catalog identifiers and the catalog period that was compared.
- `period_relation` = our period / catalog period: `same`, `2x`, `1/2x`, `3x`, `1/3x`, ... within 1 %, else `other`
  (empty when no catalog period exists). The same object is often found at a multiple or fraction of its catalog
  period: a `1/2x`, `2x` or `3x` row is the same signal as the catalog entry, not a new one.
- "New" means "not in these catalogs". It does not mean undiscovered, vetted or real.

## Totals
| sector | lots | strong | finalists |
|---|---|---|---|
| s0001 | 52 | 392 | 12 |
| s0002 | 20 | 0 | 0 |
| s0003 | 3 | 0 | 0 |
| s0005 | 5 | 0 | 0 |
| s0006 | 15 | 0 | 0 |
| s0007 | 15 | 0 | 0 |
| s0014 | 47 | 20 | 11 |
| s0015 | 16 | 2 | 0 |
| s0017 | 18 | 8 | 0 |
| s0018 | 12 | 0 | 0 |
| s0023 | 17 | 502 | 222 |
| s0026 | 8 | 0 | 0 |

## Strong rows by known status
| known_status | strong rows |
|---|---|
| known_planet | 36 |
| known_fp | 24 |
| toi_candidate | 69 |
| ctoi | 6 |
| known_eb | 35 |
| new | 754 |

New (in none of the catalogs): 754 rows, 754 distinct TICs (`candidates/new_candidates.csv`).
