# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 184,000 |
| planned total | 946,362 |
| computed share | 0.1944 |
| unstable | 152,987 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 166,701 | 13,714 |
| likely_fp | 17,252 | 17,252 |
| validated | 47 | 47 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 31,939 |
| gpu | 152,061 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5501

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
