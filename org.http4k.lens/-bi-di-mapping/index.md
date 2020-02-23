[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](./index.md)

# BiDiMapping

`class BiDiMapping<IN, OUT>`

A BiDiMapping defines a reusable bidirectional transformation between an input and output type

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A BiDiMapping defines a reusable bidirectional transformation between an input and output type`BiDiMapping(clazz: `[`Class`](https://docs.oracle.com/javase/9/docs/api/java/lang/Class.html)`<OUT>, asOut: (IN) -> OUT, asIn: (OUT) -> IN)` |

### Properties

| Name | Summary |
|---|---|
| [asIn](as-in.md) | `val asIn: (OUT) -> IN` |
| [asOut](as-out.md) | `val asOut: (IN) -> OUT` |
| [clazz](clazz.md) | `val clazz: `[`Class`](https://docs.oracle.com/javase/9/docs/api/java/lang/Class.html)`<OUT>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: OUT): IN`<br>`operator fun invoke(asIn: IN): OUT` |
| [map](map.md) | `fun <NEXT> map(nextOut: (OUT) -> NEXT, nextIn: (NEXT) -> OUT): `[`BiDiMapping`](./index.md)`<IN, NEXT>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, T> invoke(asOut: (IN) -> T, asIn: (T) -> IN): `[`BiDiMapping`](./index.md)`<IN, T>` |
