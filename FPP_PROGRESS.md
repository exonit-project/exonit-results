# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 119,239 |
| planned total | 946,362 |
| computed share | 0.1260 |
| unstable | 101,389 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 109,006 | 7,617 |
| likely_fp | 10,201 | 10,201 |
| validated | 32 | 32 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 21,198 |
| gpu | 98,041 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5397

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
