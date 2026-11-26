# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 396,684 |
| planned total | 946,362 |
| computed share | 0.4192 |
| unstable | 301,184 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 346,301 | 45,117 |
| likely_fp | 50,242 | 50,242 |
| validated | 141 | 141 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 80,147 |
| gpu | 316,537 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5011

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
