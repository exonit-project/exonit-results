# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 214,216 |
| planned total | 946,362 |
| computed share | 0.2264 |
| unstable | 175,930 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 193,089 | 17,159 |
| likely_fp | 21,067 | 21,067 |
| validated | 60 | 60 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 36,333 |
| gpu | 177,883 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5156

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
