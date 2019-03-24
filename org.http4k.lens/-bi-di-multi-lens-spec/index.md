[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMultiLensSpec](./index.md)

# BiDiMultiLensSpec

`interface BiDiMultiLensSpec<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`MultiLensSpec`](../-multi-lens-spec/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L130)

Represents a bi-directional extraction of a list of entities from a target, or an insertion into a target.

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>`<br>Make a concrete Lens for this spec that fall back to the default list of values if no values are found in the target. |
| [optional](optional.md) | `abstract fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>?>`<br>Make a concrete Lens for this spec that looks for an optional list of values in the target. |
| [required](required.md) | `abstract fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>`<br>Make a concrete Lens for this spec that looks for a required list of values in the target. |

### Inherited Functions

| Name | Summary |
|---|---|
| [defaulted](../-multi-lens-spec/defaulted.md) | `abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](../-lens/index.md)`<`[`IN`](../-multi-lens-spec/index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](../-multi-lens-spec/index.md#OUT)`>>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](../-multi-lens-spec/index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](../-multi-lens-spec/index.md#OUT)`>>`<br>Make a concrete Lens for this spec that falls back to another lens if no values are found in the target. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
