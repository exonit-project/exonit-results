# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 403,062 |
| planned total | 946,362 |
| computed share | 0.4259 |
| unstable | 304,883 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 351,201 | 46,318 |
| likely_fp | 51,714 | 51,714 |
| validated | 147 | 147 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 82,066 |
| gpu | 320,996 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +6378

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
