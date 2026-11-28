# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 425,740 |
| planned total | 946,362 |
| computed share | 0.4499 |
| unstable | 318,003 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 368,708 | 50,705 |
| likely_fp | 56,868 | 56,868 |
| validated | 164 | 164 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 88,700 |
| gpu | 337,040 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5803

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
