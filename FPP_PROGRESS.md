# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 172,806 |
| planned total | 946,362 |
| computed share | 0.1826 |
| unstable | 144,307 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 156,841 | 12,534 |
| likely_fp | 15,920 | 15,920 |
| validated | 45 | 45 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 30,544 |
| gpu | 142,262 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5652

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
