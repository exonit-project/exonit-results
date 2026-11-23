# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 288,413 |
| planned total | 946,362 |
| computed share | 0.3048 |
| unstable | 229,739 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 257,009 | 27,270 |
| likely_fp | 31,310 | 31,310 |
| validated | 94 | 94 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 47,693 |
| gpu | 240,720 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5372

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
