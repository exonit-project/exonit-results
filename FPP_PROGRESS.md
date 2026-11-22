# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 261,833 |
| planned total | 946,362 |
| computed share | 0.2767 |
| unstable | 210,647 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 234,146 | 23,499 |
| likely_fp | 27,606 | 27,606 |
| validated | 81 | 81 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 43,192 |
| gpu | 218,641 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5073

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
