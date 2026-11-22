# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 256,760 |
| planned total | 946,362 |
| computed share | 0.2713 |
| unstable | 207,030 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 229,790 | 22,760 |
| likely_fp | 26,892 | 26,892 |
| validated | 78 | 78 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 42,143 |
| gpu | 214,617 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5206

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
