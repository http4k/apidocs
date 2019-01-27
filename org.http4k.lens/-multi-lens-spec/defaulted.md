[http4k](../../index.md) / [org.http4k.lens](../index.md) / [MultiLensSpec](index.md) / [defaulted](./defaulted.md)

# defaulted

`abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L41)

Make a concrete Lens for this spec that fall back to the default list of values if no values are found in the target.

`abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L46)

Make a concrete Lens for this spec that falls back to another lens if no values are found in the target.

