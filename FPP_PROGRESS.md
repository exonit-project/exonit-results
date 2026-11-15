# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 54,357 |
| planned total | 946,362 |
| computed share | 0.0574 |
| unstable | 46,791 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 49,791 | 3,000 |
| likely_fp | 4,552 | 4,552 |
| validated | 14 | 14 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 9,373 |
| gpu | 44,984 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5404

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
