# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 81,392 |
| planned total | 946,362 |
| computed share | 0.0860 |
| unstable | 69,846 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 74,573 | 4,727 |
| likely_fp | 6,798 | 6,798 |
| validated | 21 | 21 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 13,301 |
| gpu | 68,091 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5329

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
