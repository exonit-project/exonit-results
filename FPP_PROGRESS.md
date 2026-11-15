# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 76,063 |
| planned total | 946,362 |
| computed share | 0.0804 |
| unstable | 65,414 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 69,750 | 4,336 |
| likely_fp | 6,293 | 6,293 |
| validated | 20 | 20 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 12,523 |
| gpu | 63,540 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5151

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
