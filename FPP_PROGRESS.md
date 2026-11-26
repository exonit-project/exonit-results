# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 384,469 |
| planned total | 946,362 |
| computed share | 0.4063 |
| unstable | 293,904 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 336,724 | 42,820 |
| likely_fp | 47,613 | 47,613 |
| validated | 132 | 132 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 76,454 |
| gpu | 308,015 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5394

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
