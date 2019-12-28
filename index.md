# FTL crew speed measurements

## Summary of results

The in-game descriptions are not quite accurate. Rocks and Crystals are slightly faster than expected, Mantis slightly slower.

Mantis Pheromones has slightly less effect than advertised. It says 25% faster, but it's actually 23% faster.

|         | Speed vs. human | Seconds per tile | Tiles per second |
|---------|:---------------:|:----------------:|:----------------:|
| Human   | 1               | 0.46             | 2.19             |
| Engi    | 1               | 0.46             | 2.19             |
| Slug    | 1               | 0.46             | 2.19             |
| Zoltan  | 1               | 0.46             | 2.19             |
| Mantis  | 1.18            | 0.39             | 2.59             |
| Rock    | 0.51            | 0.89             | 1.12             |
| Crystal | 0.81            | 0.56             | 1.78             |
| Lanius  | 0.85            | 0.53             | 1.86             |

## Method of testing

Tests used Mantis C, running circles from Piloting --> Shields --> Teleporter --> Piloting. Each test was 10 laps, so 240 tiles total movement.

I used timer software with stop/start bound to the FTL pause buttons. Crew movement was continuous with no diversions, pausing only at the end of lap 10. Mantis Pheromones were sold before starting (except when testing the augment itself).

I took the mean of only 3 measurements for each race, since the results were always extremely close. The small difference in timing is explained by small differences in pausing at the end of the last lap.

## Full test data

### Time for 240 tiles, without Mantis Pheromones

Because the first four races are so extremely close, I pooled their results when calculating the summary. It would be silly to say that Humans are 99.91% as fast as Slugs.

|          | Human  | Engi   | Slug   | Zoltan | Mantis | Rock   | Crystal | Lanius |
|:--------:|:------:|:------:|:------:|:------:|:------:|:------:|:-------:|:------:|
| **1**    | 109.51 | 109.37 | 109.67 | 109.57 | 92.84  | 213.34 | 135.08  | 128.38 |
| **2**    | 109.59 | 109.65 | 109.64 | 109.57 | 92.86  | 213.46 | 135.08  | 128.55 |
| **3**    | 109.51 | 109.59 | 109.60 | 109.54 | 92.83  | 213.53 | 135.07  | 128.68 |

Markdown errors?

|               | Human Engi Slug Zoltan | Mantis | Rock    | Crystal  | Lanius  |
|:-------------:|:----------------------:|:-------:|:--------:|:-------:|:--------:|
| **Mean time** | 109.5675               | 92.8433 | 213.4433 | 135.0767 | 128.5367 |

### Time with Mantis Pheromones

I only tested this with a Human.

| 1     | 2     | 3     | Mean    |
|:-----:|:-----:|:-----:|:-------:|
| 89.08 | 88.97 | 89.15 | 89.0667 |
