# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 414,893 |
| planned total | 946,362 |
| computed share | 0.4384 |
| unstable | 311,804 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 360,366 | 48,562 |
| likely_fp | 54,370 | 54,370 |
| validated | 157 | 157 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 85,455 |
| gpu | 329,438 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5367

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
