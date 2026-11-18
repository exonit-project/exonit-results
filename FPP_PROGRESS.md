# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 140,410 |
| planned total | 946,362 |
| computed share | 0.1484 |
| unstable | 118,653 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 128,074 | 9,421 |
| likely_fp | 12,298 | 12,298 |
| validated | 38 | 38 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 25,054 |
| gpu | 115,356 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5345

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
