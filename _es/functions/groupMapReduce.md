---
name: groupMapReduce
---

# `groupMapReduce`

@include [signatures/groupMapReduce.md]

`groupMapReduce` crea un `Map` agrupando los elementos bajo la clave emitida por la función `k` cuando se les es aplicada, aplicando la función de transformación `f` a los elementos agrupados y finalmente reduciendo los elementos transformados utilizando el operador binario asociativo `op`.

@include [figure.html source="../images/groupMapReduce.svg" desc="Diagram of the function groupMapReduce"]
