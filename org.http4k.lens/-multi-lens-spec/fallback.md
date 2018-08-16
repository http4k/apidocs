[http4k](../../index.md) / [org.http4k.lens](../index.md) / [MultiLensSpec](index.md) / [fallback](./fallback.md)

# fallback

`abstract fun fallback(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, fallback: `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`OUT`](index.md#OUT)`>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L50)

Make a concrete Lens for this spec that falls back to another lens if no values are found in the target.

