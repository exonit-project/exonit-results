# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 209,060 |
| planned total | 946,362 |
| computed share | 0.2209 |
| unstable | 172,073 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 188,608 | 16,535 |
| likely_fp | 20,396 | 20,396 |
| validated | 56 | 56 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 35,539 |
| gpu | 173,521 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5043

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
