# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 102,828 |
| planned total | 946,362 |
| computed share | 0.1087 |
| unstable | 87,771 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 94,106 | 6,335 |
| likely_fp | 8,698 | 8,698 |
| validated | 24 | 24 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 17,686 |
| gpu | 85,142 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5735

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
