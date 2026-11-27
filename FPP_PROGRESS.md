# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 409,526 |
| planned total | 946,362 |
| computed share | 0.4327 |
| unstable | 308,718 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 356,191 | 47,473 |
| likely_fp | 53,181 | 53,181 |
| validated | 154 | 154 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 83,885 |
| gpu | 325,641 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +6464

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
