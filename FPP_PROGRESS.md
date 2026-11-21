# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 229,925 |
| planned total | 946,362 |
| computed share | 0.2430 |
| unstable | 187,532 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 206,651 | 19,119 |
| likely_fp | 23,206 | 23,206 |
| validated | 68 | 68 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 38,386 |
| gpu | 191,539 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5479

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
