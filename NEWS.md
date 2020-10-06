# mlearning News

## Change in mlearning 1.0.5

* In `mlLvq()` providing `size =` or `prior =` led to an `lvq` object not found
message. Corrected.

## Changes in mlearning 1.0.4

* Sometines, data was not found (e.g., when called inside a learnr).

* In mlearning(), data is forced with `as.data.frame()` (tibbles are not
supported internally).

* In the `mlXXX()` function, it was not possible to indicate something like
`mlLda(data = iris, Species ~ .)`. Solved by adding `train =` argument in
`mlXXX()`.

* In `summary.confusion()` produced an error if more than one `type =` was
provided.

## Changes in mlearning 1.0.3

* NEWS.md file added. Repository moved to Github.
