---
category: minorAnalysis
---
* The query `go/insecure-randomness` now recognizes the selection of candidates from a predefined set using a weak RNG when the result is used in a sensitive operation. Also, false positives have been reduced by adding more sink exclusions for functions in the `crypto` package not related to cryptographic operations.
