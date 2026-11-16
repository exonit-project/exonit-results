# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 97,093 |
| planned total | 946,362 |
| computed share | 0.1026 |
| unstable | 82,982 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 88,863 | 5,881 |
| likely_fp | 8,206 | 8,206 |
| validated | 24 | 24 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 16,557 |
| gpu | 80,536 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5448

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
