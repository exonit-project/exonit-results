# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 251,554 |
| planned total | 946,362 |
| computed share | 0.2658 |
| unstable | 203,284 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 225,328 | 22,044 |
| likely_fp | 26,149 | 26,149 |
| validated | 77 | 77 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 41,297 |
| gpu | 210,257 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5340

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
