# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 267,367 |
| planned total | 946,362 |
| computed share | 0.2825 |
| unstable | 214,543 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 238,850 | 24,307 |
| likely_fp | 28,434 | 28,434 |
| validated | 83 | 83 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 43,881 |
| gpu | 223,486 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5534

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
