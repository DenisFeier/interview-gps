# GPS Coordinates

## Task

Given a list of coordinates and an origin coordinate, find the first `n` closest coordinates to the origin based on their Euclidean distance.

### Coordinates

A pair of numbers representing a point in a 2D space, e.g., (x, y).

### Example

For `[[1, 2], [3, 4], [1, -1], [2, 2], [5, 3]]` we should get `[[1, -1], [1, 2], [2, 2]]` for `n = 3` and origin `[0, 0]`.

### Formula

```distance = sqrt((x2 - x1)^2 + (y2 - y1)^2)```

### Test Case

Given the list of coordinates `[[1, 2], [3, 4], [1, -1], [2, 2], [5, 3]]` and the origin `[0, 0]`, find the 3 closest coordinates to the origin.

Expected output: `[[1, -1], [1, 2], [2, 2]]`
