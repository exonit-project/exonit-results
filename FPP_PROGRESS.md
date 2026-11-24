# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 330,814 |
| planned total | 946,362 |
| computed share | 0.3496 |
| unstable | 258,855 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 292,594 | 33,739 |
| likely_fp | 38,111 | 38,111 |
| validated | 109 | 109 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 59,379 |
| gpu | 271,435 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5016

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
