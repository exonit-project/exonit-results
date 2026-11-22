# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 272,454 |
| planned total | 946,362 |
| computed share | 0.2879 |
| unstable | 218,133 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 243,164 | 25,031 |
| likely_fp | 29,203 | 29,203 |
| validated | 87 | 87 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 44,659 |
| gpu | 227,795 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5087

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
