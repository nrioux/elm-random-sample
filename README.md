# Random.Array
by Max Goldstein

** NOT UPDATED FOR 0.17**, see [elm-random-extra](http://package.elm-lang.org/packages/elm-community/elm-random-extra/latest/Random-Array) for equivalent functions.

Randomized functions on the Array data structure in Elm 0.16. Previously published
as `Elm-Random-Sampling` for 0.15.

The implementations seem robust but should not be trusted when cryptographic
randomness is required. Tests of the shuffle algorithm are available in
`test/grid.elm` and `test/reference.html`.

Please submit issues and bugs through GitHub. Particularly welcome are
performance optimizations and (dis)proofs of statistical randomness.
