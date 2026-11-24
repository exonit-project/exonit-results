# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 320,571 |
| planned total | 946,362 |
| computed share | 0.3387 |
| unstable | 252,037 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 284,160 | 32,123 |
| likely_fp | 36,307 | 36,307 |
| validated | 104 | 104 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 56,455 |
| gpu | 264,116 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +5389

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
