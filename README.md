## The drake R package: reproducible computation at scale

The [`drake` R package](https://github.com/ropensci/drake) is a general-purpose workflow manager for data-driven tasks in R. It rebuilds intermediate data objects when their dependencies change, and it skips work when the results are already up to date. Not every runthrough starts from scratch, there is native support for parallel and distributed computing, and completed workflows have tangible evidence of reproducibility. This presentation introduces `drake` using a simple practical example from the social sciences.
