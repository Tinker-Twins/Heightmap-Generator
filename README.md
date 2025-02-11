# Heightmap Generator Using Diamond-Square Algorithm

The [diamond-square algorithm](https://en.wikipedia.org/wiki/Diamond-square_algorithm) is a method for generating [heightmaps](https://en.wikipedia.org/wiki/Heightmap) for computer graphics and can be used to [procedurally](https://en.wikipedia.org/wiki/Procedural_textures) generate realistic landscapes. It is also known as the random midpoint displacement fractal, the cloud fractal or the plasma fractal.

- **The diamond step:** For each square in the array, set the midpoint of that square to be the average of the four corner points plus a random value.
- **The square step:** For each diamond in the array, set the midpoint of that diamond to be the average of the four corner points plus a random value.
