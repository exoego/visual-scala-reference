---
name: foldRight
---

# `foldRight`

@include [signatures/foldRight.md]

`foldRight` applies the binary operator `op` to each element, going from right to left, and the previous `op` result. The first time `op` is applied it's fed with the initial value `z`.

@include [figure.html source="images/foldRight.svg" desc="Diagram of the function foldRight"]

On empty collections this function doesn't apply `op` and the initial value `z` is directly returned.

@include [figure.html source="images/foldRight.2.svg" desc="Diagram of the function foldRight"]

