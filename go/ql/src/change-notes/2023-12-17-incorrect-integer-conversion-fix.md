---
category: minorAnalysis
---
* There was a bug in the query `go/incorrect-integer-conversion` which meant that upper bound checks using a strict inequality (`<`) and comparing against `math.MaxInt` or `math.MaxUint` were not considered correctly, which led to false positives. This has now been fixed.
