# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 341,166 |
| planned total | 946,362 |
| computed share | 0.3605 |
| unstable | 265,585 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 301,058 | 35,473 |
| likely_fp | 39,992 | 39,992 |
| validated | 116 | 116 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 62,537 |
| gpu | 278,629 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5251

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
