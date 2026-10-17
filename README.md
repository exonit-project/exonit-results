> **Notice (2026-10-18): contributions paused.** These results are being recomputed with a revised pipeline. Pull requests and issues are paused until the next release.
>
> **Notice (2026-10-17): false-positive probabilities withdrawn.** The false-positive probability (FPP) values that used to be listed here, and the `tri_*` labels derived from them, were withdrawn because the model that produced them had known defects; a corrected model is in progress, and the values will be recomputed and republished. The candidate classifier score (`clf_planet_candidate`) used FPP as one of its inputs, so rankings may shift after the recompute. Until then, please do not use these tables to rank or dismiss candidates.
>
> *2026-10-17 - Withdrew all FPP/NFPP values and the FPP-derived tier labels (shown as `fpp_withheld`); a corrected model is in progress and every value will be recomputed.*

# ExoNit — public results

> **Experimental — personal research project (Confidence Level L0).** Results are not validated by an
> astrophysicist. These are raw pipeline outputs. **Do NOT submit anything here to ExoFOP** and do not make
> scientific claims based on it. See [CONFIDENCE_LEDGER.md](CONFIDENCE_LEDGER.md).

Generated 2026-10-14T14:51:28Z from internal commit `b926fc7b82b2bef69de304c9762a50acb8aa8e13` by `scripts/release/build_public_results.py`
of [exonit-public](https://github.com/marc252/exonit-public). Everything here is generated (FPP values withheld afterwards by a post-processing step); do not edit by hand.

## What is here
- `sectors/s<NNNN>/summary.md` — one row per processed lot (TICs completed, failed, strong candidates, finalists).
- `sectors/s<NNNN>/lots/<run_id>.json` — the lot scorecard (recall vs the TOI catalog by depth/period/sectors,
  period/depth/duration precision, false-positive rates per stage). `<run_id>_dossier.md` — the vetting dossier
  (strong candidates after the systematic-family veto, finalists, shared-signal cross-check, cross-sector queue).
- `candidates/strong_candidates.csv` — every strong-candidate row from every dossier, with its `pipeline_label`
  and the catalog cross-match columns.
- `candidates/new_candidates.csv` — only the rows found in none of the catalogs;
  `candidates/crossmatch_sources.json` — exactly which catalogs, versions and retrieval time were used.
- `benchmarks/` — the latest blind TOI benchmark (recall of KP/CP/PC hosts processed with TGLC light curves).
- `INDEX.json` — machine-readable totals.

## How to read `pipeline_label`
The label is a raw pipeline output. **None of these labels is a disposition, a validation or a confirmation:** no
follow-up observations (spectroscopy, high-resolution imaging, ground-based photometry) were used for any of them.

| pipeline_label | what it means |
|---|---|
| `fpp_withheld` | Replaces the former FPP-derived tier labels. FPP (false-positive probability) is withheld, see the notice at the top: the labels were derived from FPP values produced by a model with known defects, and will be republished after a recompute. |
| `tri_failed` | The TRICERATOPS run failed (no FPP). |
| `unscored` | No TRICERATOPS result was available when the dossier was written. |
| `clf_planet_candidate` | The gradient-boosted verdict classifier scored above its threshold on the pipeline's own features. A classifier score is not a disposition. |

Older dossiers used different words for the FPP-derived labels; all of them now read `fpp_withheld`.

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
| s0007 | 8 | 0 | 0 |
| s0014 | 47 | 20 | 11 |
| s0015 | 16 | 2 | 0 |
| s0017 | 18 | 8 | 0 |
| s0018 | 12 | 0 | 0 |
| s0023 | 17 | 502 | 224 |
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
