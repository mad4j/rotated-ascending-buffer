# rotated-ascending-buffer
Find max value in a rotated ascending buffer

```
  Original (Sorted)                                            Rotated (Rotated Ascending Buffer)
  ----------------------                                       -------------------------------
    1     2     3     4     5     6     7     8     9          5     6     7     8     9     1     2     3     4
    |     |     |     |     |     |     |     |     |          |     |     |     |     |     |     |     |     |
    V     V     V     V     V     V     V     V     V          V     V     V     V     V     V     V     V     V
  ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐      ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐ ┌───┐
  │ 1 │ │ 2 │ │ 3 │ │ 4 │ │ 5 │ │ 6 │ │ 7 │ │ 8 │ │ 9 │  ->  │ 5 │ │ 6 │ │ 7 │ │ 8 │ │ 9 │ │ 1 │ │ 2 │ │ 3 │ │ 4 │
  └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘      └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘ └───┘
                                                                                       ^
                                                                                     pivot
```
