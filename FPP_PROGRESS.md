# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 86,595 |
| planned total | 946,362 |
| computed share | 0.0915 |
| unstable | 74,164 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 79,273 | 5,109 |
| likely_fp | 7,300 | 7,300 |
| validated | 22 | 22 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 14,669 |
| gpu | 71,926 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5203

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
