---
name: reduceOption
---

# `reduceOption`

@include [signatures/reduceOption.md]

`reduceOption` applies the binary operator `op` to pairs of elements in this collection until the final result is calculated and returned wrapped with `Some`.

@include [figure.html source="images/reduceOption.svg" desc="Diagram of the function reduceOption"]

On empty collections this function returns `None`.

@include [figure.html source="images/reduceOption.2.svg" desc="Diagram of the function reduceOption"]
