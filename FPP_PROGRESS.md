# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 298,787 |
| planned total | 946,362 |
| computed share | 0.3157 |
| unstable | 237,273 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 266,055 | 28,782 |
| likely_fp | 32,637 | 32,637 |
| validated | 95 | 95 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 50,595 |
| gpu | 248,192 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5243

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
