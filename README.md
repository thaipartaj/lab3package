# lab3package

## Authors

| Name | LiU-ID | GitHub |
| --- | --- | --- |
| Hampus Beijer | ditt LiU-ID | [HBeijer](https://github.com/HBeijer) |
| Thai Pham | Thais LiU-ID | [thaipartaj](https://github.com/thaipartaj) |
<!-- badges: start -->
[![R-CMD-check](https://github.com/thaipartaj/lab3package/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/thaipartaj/lab3package/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

This package provides functions that implement the Euclidean algorithm and Dijkstra’s algorithm.

## Installation

The package can be installed directly from GitHub:

```r
install.packages("pak") # Run this line if pak is not already installed
pak::pak("thaipartaj/lab3package")
```

## Examples

Load the package:

```r
library(lab3package)
```

The Euclidean algorithm finds the greatest common divisor (GCD) of two numbers:

```r
euclidean(100, 75)
# [1] 25
```

Dijkstra’s algorithm finds the shortest distance from a specified node to every other node in a graph.

```r
dijkstra(wiki_graph, 1)
# [1] 0  7  9 20 20 11
```

