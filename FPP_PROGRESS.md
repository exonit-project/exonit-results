# FPP progress

FPP values computed with the current engine, one per candidate signal; a candidate signal is a periodic dip found by the search, most are not planets.

| item | value |
| --- | ---: |
| computed | 354,774 |
| planned total | 946,362 |
| computed share | 0.3749 |
| unstable | 275,208 |
| imported in force | 218,514 |
| imported synthetic aperture | 1 |
| invalid only | 0 |

## By verdict

| verdict | computed | stable |
| --- | ---: | ---: |
| candidate | 312,867 | 37,659 |
| likely_fp | 41,785 | 41,785 |
| validated | 122 | 122 |

## By device kind

| device kind | computed |
| --- | ---: |
| cpu | 67,013 |
| gpu | 287,761 |

**Unstable**: the Monte-Carlo estimate rests on too few effective samples of its dominant scenario: the value can change if recomputed, and such a result is never reported above 'candidate'.

since the previous publication: +6109

What is not being recomputed is listed in `FPP_NOT_RECOMPUTED.md`.

Detailed values are published for the strong candidates only (`candidates/strong_candidates.csv`).
