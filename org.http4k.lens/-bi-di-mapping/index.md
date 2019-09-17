[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMapping](./index.md)

# BiDiMapping

`class BiDiMapping<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/BiDiMapping.kt#L34)

A BiDiMapping defines a reusable bidirectional transformation between an input and output type

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiMapping(clazz: `[`Class`](https://docs.oracle.com/javase/9/docs/api/java/lang/Class.html)`<`[`OUT`](index.md#OUT)`>, asOut: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT)`, asIn: (`[`OUT`](index.md#OUT)`) -> `[`IN`](index.md#IN)`)`<br>A BiDiMapping defines a reusable bidirectional transformation between an input and output type |

### Properties

| Name | Summary |
|---|---|
| [asIn](as-in.md) | `val asIn: (`[`OUT`](index.md#OUT)`) -> `[`IN`](index.md#IN) |
| [asOut](as-out.md) | `val asOut: (`[`IN`](index.md#IN)`) -> `[`OUT`](index.md#OUT) |
| [clazz](clazz.md) | `val clazz: `[`Class`](https://docs.oracle.com/javase/9/docs/api/java/lang/Class.html)`<`[`OUT`](index.md#OUT)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(out: `[`OUT`](index.md#OUT)`): `[`IN`](index.md#IN)<br>`operator fun invoke(asIn: `[`IN`](index.md#IN)`): `[`OUT`](index.md#OUT) |
| [map](map.md) | `fun <NEXT> map(nextOut: (`[`OUT`](index.md#OUT)`) -> `[`NEXT`](map.md#NEXT)`, nextIn: (`[`NEXT`](map.md#NEXT)`) -> `[`OUT`](index.md#OUT)`): `[`BiDiMapping`](./index.md)`<`[`IN`](index.md#IN)`, `[`NEXT`](map.md#NEXT)`>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <IN, T> invoke(asOut: (`[`IN`](invoke.md#IN)`) -> `[`T`](invoke.md#T)`, asIn: (`[`T`](invoke.md#T)`) -> `[`IN`](invoke.md#IN)`): `[`BiDiMapping`](./index.md)`<`[`IN`](invoke.md#IN)`, `[`T`](invoke.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
