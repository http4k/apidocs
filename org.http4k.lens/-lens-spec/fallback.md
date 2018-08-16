[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSpec](index.md) / [fallback](./fallback.md)

# fallback

`open fun fallback(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, fallback: `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<`[`IN`](index.md#IN)`, `[`OUT`](index.md#OUT)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/lensSpec.kt#L84)

Make a concrete Lens for this spec that falls back to another lens if no value is found in the target.

