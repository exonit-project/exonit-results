# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 198,643 |
| planned total | 946,362 |
| computed share | 0.2099 |
| unstable | 164,201 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 179,547 | 15,346 |
| likely_fp | 19,044 | 19,044 |
| validated | 52 | 52 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 34,183 |
| gpu | 164,460 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +9121

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
