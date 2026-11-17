# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 108,673 |
| planned total | 946,362 |
| computed share | 0.1148 |
| unstable | 92,634 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 99,417 | 6,783 |
| likely_fp | 9,231 | 9,231 |
| validated | 25 | 25 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 18,956 |
| gpu | 89,717 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5845

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
