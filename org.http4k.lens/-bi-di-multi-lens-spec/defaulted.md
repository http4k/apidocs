[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMultiLensSpec](index.md) / [defaulted](./defaulted.md)

# defaulted

`abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<IN, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>>`

Make a concrete Lens for this spec that fall back to the default list of values if no values are found in the target.

