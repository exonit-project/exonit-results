# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 372,061 |
| planned total | 946,362 |
| computed share | 0.3931 |
| unstable | 286,310 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 326,965 | 40,655 |
| likely_fp | 44,969 | 44,969 |
| validated | 127 | 127 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 72,670 |
| gpu | 299,391 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5834

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
