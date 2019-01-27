[http4k](../../index.md) / [org.http4k.lens](../index.md) / [MultiLensSpec](./index.md)

# MultiLensSpec

`interface MultiLensSpec<IN, OUT>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L37)

Represents a uni-directional extraction of a list of entities from a target.

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | `abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>`<br>Make a concrete Lens for this spec that fall back to the default list of values if no values are found in the target.`abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>`<br>Make a concrete Lens for this spec that falls back to another lens if no values are found in the target. |
| [optional](optional.md) | `abstract fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>?>`<br>Make a concrete Lens for this spec that looks for an optional list of values in the target. |
| [required](required.md) | `abstract fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>`<br>Make a concrete Lens for this spec that looks for a required list of values in the target. |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiMultiLensSpec](../-bi-di-multi-lens-spec/index.md) | `interface BiDiMultiLensSpec<IN, OUT> : `[`MultiLensSpec`](./index.md)`<`[`IN`](../-bi-di-multi-lens-spec/index.md#IN)`, `[`OUT`](../-bi-di-multi-lens-spec/index.md#OUT)`>`<br>Represents a bi-directional extraction of a list of entities from a target, or an insertion into a target. |
