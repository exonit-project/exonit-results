# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 283,041 |
| planned total | 946,362 |
| computed share | 0.2991 |
| unstable | 225,705 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 252,255 | 26,550 |
| likely_fp | 30,697 | 30,697 |
| validated | 89 | 89 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 46,468 |
| gpu | 236,573 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5411

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
