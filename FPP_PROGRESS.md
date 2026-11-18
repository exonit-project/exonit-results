# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 156,481 |
| planned total | 946,362 |
| computed share | 0.1654 |
| unstable | 131,498 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 142,380 | 10,882 |
| likely_fp | 14,059 | 14,059 |
| validated | 42 | 42 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 27,727 |
| gpu | 128,754 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5491

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
