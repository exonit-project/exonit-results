# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 145,633 |
| planned total | 946,362 |
| computed share | 0.1539 |
| unstable | 122,820 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 132,716 | 9,896 |
| likely_fp | 12,877 | 12,877 |
| validated | 40 | 40 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 26,118 |
| gpu | 119,515 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5223

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
