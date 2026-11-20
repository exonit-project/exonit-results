# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 204,017 |
| planned total | 946,362 |
| computed share | 0.2156 |
| unstable | 168,273 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 184,233 | 15,960 |
| likely_fp | 19,729 | 19,729 |
| validated | 55 | 55 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 34,768 |
| gpu | 169,249 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5374

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
