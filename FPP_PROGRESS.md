# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 235,244 |
| planned total | 946,362 |
| computed share | 0.2486 |
| unstable | 191,411 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 211,258 | 19,847 |
| likely_fp | 23,917 | 23,917 |
| validated | 69 | 69 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 39,058 |
| gpu | 196,186 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5319

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
