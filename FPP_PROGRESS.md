# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 124,429 |
| planned total | 946,362 |
| computed share | 0.1315 |
| unstable | 105,679 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 113,727 | 8,048 |
| likely_fp | 10,669 | 10,669 |
| validated | 33 | 33 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 22,461 |
| gpu | 101,968 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5190

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
