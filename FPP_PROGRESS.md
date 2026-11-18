# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 161,792 |
| planned total | 946,362 |
| computed share | 0.1710 |
| unstable | 135,715 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 147,094 | 11,379 |
| likely_fp | 14,655 | 14,655 |
| validated | 43 | 43 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 28,618 |
| gpu | 133,174 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5311

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
