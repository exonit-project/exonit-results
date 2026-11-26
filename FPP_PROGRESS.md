# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 391,673 |
| planned total | 946,362 |
| computed share | 0.4139 |
| unstable | 298,139 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 342,378 | 44,239 |
| likely_fp | 49,156 | 49,156 |
| validated | 139 | 139 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 78,662 |
| gpu | 313,011 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +7204

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
