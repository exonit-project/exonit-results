# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 38,177 |
| planned total | 946,362 |
| computed share | 0.0403 |
| unstable | 32,862 |
| imported in force | 218,515 |
| imported synthetic aperture | 2 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 34,946 | 2,084 |
| likely_fp | 3,221 | 3,221 |
| validated | 10 | 10 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 7,141 |
| gpu | 31,036 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5632

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
