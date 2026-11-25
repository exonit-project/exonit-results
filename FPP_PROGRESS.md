# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 360,961 |
| planned total | 946,362 |
| computed share | 0.3814 |
| unstable | 279,327 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 318,051 | 38,724 |
| likely_fp | 42,785 | 42,785 |
| validated | 125 | 125 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 69,033 |
| gpu | 291,928 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +6187

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
