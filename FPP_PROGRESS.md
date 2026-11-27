# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 419,937 |
| planned total | 946,362 |
| computed share | 0.4437 |
| unstable | 314,745 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 364,295 | 49,550 |
| likely_fp | 55,480 | 55,480 |
| validated | 162 | 162 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 86,864 |
| gpu | 333,073 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5044

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
