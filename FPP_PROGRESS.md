# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 70,912 |
| planned total | 946,362 |
| computed share | 0.0749 |
| unstable | 61,034 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 65,025 | 3,991 |
| likely_fp | 5,868 | 5,868 |
| validated | 19 | 19 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 11,791 |
| gpu | 59,121 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5346

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
