# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 219,404 |
| planned total | 946,362 |
| computed share | 0.2318 |
| unstable | 179,736 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 197,518 | 17,782 |
| likely_fp | 21,825 | 21,825 |
| validated | 61 | 61 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 36,948 |
| gpu | 182,456 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5188

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
