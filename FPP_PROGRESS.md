# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 129,829 |
| planned total | 946,362 |
| computed share | 0.1372 |
| unstable | 110,041 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 118,557 | 8,516 |
| likely_fp | 11,237 | 11,237 |
| validated | 35 | 35 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 23,556 |
| gpu | 106,273 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5400

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
