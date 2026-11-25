# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 348,665 |
| planned total | 946,362 |
| computed share | 0.3684 |
| unstable | 270,972 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 307,580 | 36,608 |
| likely_fp | 40,966 | 40,966 |
| validated | 119 | 119 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 65,045 |
| gpu | 283,620 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +7499

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
