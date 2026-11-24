# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 315,182 |
| planned total | 946,362 |
| computed share | 0.3330 |
| unstable | 248,418 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 279,711 | 31,293 |
| likely_fp | 35,370 | 35,370 |
| validated | 101 | 101 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 55,005 |
| gpu | 260,177 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5624

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
