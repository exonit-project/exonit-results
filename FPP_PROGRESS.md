# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 224,446 |
| planned total | 946,362 |
| computed share | 0.2372 |
| unstable | 183,489 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 201,898 | 18,409 |
| likely_fp | 22,482 | 22,482 |
| validated | 66 | 66 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 37,651 |
| gpu | 186,795 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5042

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
