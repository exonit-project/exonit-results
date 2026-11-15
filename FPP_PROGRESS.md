# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 65,566 |
| planned total | 946,362 |
| computed share | 0.0693 |
| unstable | 56,455 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 60,103 | 3,648 |
| likely_fp | 5,446 | 5,446 |
| validated | 17 | 17 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 11,071 |
| gpu | 54,495 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5927

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
