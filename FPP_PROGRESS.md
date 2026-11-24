# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 325,798 |
| planned total | 946,362 |
| computed share | 0.3443 |
| unstable | 255,588 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 288,479 | 32,891 |
| likely_fp | 37,212 | 37,212 |
| validated | 107 | 107 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 57,898 |
| gpu | 267,900 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5227

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
