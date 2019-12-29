# FTL crew speed measurements

## Summary of results

Crew are slowed slightly by doors (open or closed). To an even smaller extent, they appear to be slowed by changes in direction. Here are the speeds for a Human:

|             | Description     | Tiles per second | Seconds per tile |
|:-----------:|:---------------:|:----------------:|:----------------:|
| **Fastest** | No doors        | 2.28             | 0.438            |
| **Slowest** | A maze of doors | 2.17             | 0.460            | 

Possibly as a result of this, the game's description of crew speeds (and Mantis Pheromones) are not quite accurate in "real-world" conditions. The following times are from tests running around the Mantis C:

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

Mantis Pheromones gave about a 23% boost here, not the advertised 25%.

## Test methods and data

### "Realistic" tests (Mantis C)

These tests used Mantis C, running circles from Piloting --> Shields --> Teleporter --> Piloting. Each test was 10 laps, so 240 tiles total movement.

I used timer software with stop/start bound to the FTL pause buttons. Crew movement was continuous with no diversions, pausing only at the end of lap 10. Mantis Pheromones were sold before starting (except when testing the augment itself).

I took the mean of only 3 measurements for each race, since the results were always extremely close. The small difference in timing is explained by small differences in pausing at the end of the last lap.

|          | Human  | Engi   | Slug   | Zoltan | Mantis | Rock   | Crystal | Lanius |
|:--------:|:------:|:------:|:------:|:------:|:------:|:------:|:-------:|:------:|
| **1**    | 109.51 | 109.37 | 109.67 | 109.57 | 92.84  | 213.34 | 135.08  | 128.38 |
| **2**    | 109.59 | 109.65 | 109.64 | 109.57 | 92.86  | 213.46 | 135.08  | 128.55 |
| **3**    | 109.51 | 109.59 | 109.60 | 109.54 | 92.83  | 213.53 | 135.07  | 128.68 |

Because the first four races are so extremely close, I pooled their results when calculating the mean and derived values. It would be silly to say that Slugs are 99.91% as fast as Humans.

|               | Human, Engi, Slug, Zoltan | Mantis  | Rock     | Crystal  | Lanius   |
|:-------------:|:-------------------------:|:-------:|:--------:|:--------:|:--------:|
| **Mean time** | 109.5675                  | 92.8433 | 213.4433 | 135.0767 | 128.5367 |

For Mantis Pheromones, I only did 3 tests with a Human:

| 1     | 2     | 3     | Mean    |
|:-----:|:-----:|:-----:|:-------:|
| 89.08 | 88.97 | 89.15 | 89.0667 |

### "Synthetic" tests

I recorded these on video ([main](https://www.youtube.com/watch?v=a481S5b5vDQ), [extra](https://www.youtube.com/watch?v=Z_x1SBK24yo)). These tests used custom layouts and Humans only (no Pheromones). Each scenario was tested twice (once in each direction).

| Description                                             | Number of tiles | Time         | Tiles per second |
|---------------------------------------------------------|-----------------|--------------|------------------|
| Horizontal movement with few doors or direction changes | 149             | 65.45, 65.48 | 2.28             |
| As above, but with lots of doors                        | 149             | 68.08, 67.79 | 2.19             |
| As above, but with the doors open                       | 149             | 68.08, 67.96 | 2.19             |
| "Maze" with constant changes of direction (and doors)   | 149             | 68.50, 68.54 | 2.17             |
| Vertical movement with few doors or direction changes   | 149             | 65.46, 65.68 | 2.27             |
| Pure diagonal movement, no doors                        | 12.73           | 5.60, 5.55   | 2.28             |
| "Diagonal" movement across square rooms                 | 71.43*          | 32.15, 32.22 | 2.22             |

\* 30 diagonal movements and 29 straight movements. A diagonal movement *should* be √2 tiles distance (about 1.41).
