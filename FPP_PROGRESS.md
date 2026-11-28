# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 438,357 |
| planned total | 946,362 |
| computed share | 0.4632 |
| unstable | 324,873 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 378,252 | 53,379 |
| likely_fp | 59,926 | 59,926 |
| validated | 179 | 179 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 92,601 |
| gpu | 345,756 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5714

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
