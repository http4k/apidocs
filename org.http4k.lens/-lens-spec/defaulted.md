[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSpec](index.md) / [defaulted](./defaulted.md)

# defaulted

`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: OUT, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT>`

Make a concrete Lens for this spec that falls back to the default value if no value is found in the target.

`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](../-lens/index.md)`<IN, OUT>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT>`

Make a concrete Lens for this spec that falls back to another lens if no value is found in the target.

