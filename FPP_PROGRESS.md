# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 379,075 |
| planned total | 946,362 |
| computed share | 0.4006 |
| unstable | 290,560 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 332,485 | 41,925 |
| likely_fp | 46,459 | 46,459 |
| validated | 131 | 131 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 74,881 |
| gpu | 304,194 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +7014

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
