# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 240,329 |
| planned total | 946,362 |
| computed share | 0.2540 |
| unstable | 195,134 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 215,666 | 20,532 |
| likely_fp | 24,592 | 24,592 |
| validated | 71 | 71 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 39,821 |
| gpu | 200,508 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5085

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
