[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiMultiLensSpec](./index.md)

# BiDiMultiLensSpec

`interface BiDiMultiLensSpec<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`MultiLensSpec`](../-multi-lens-spec/index.md)`<IN, OUT>`

Represents a bi-directional extraction of a list of entities from a target, or an insertion into a target.

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | Make a concrete Lens for this spec that fall back to the default list of values if no values are found in the target.`abstract fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<IN, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>>` |
| [optional](optional.md) | Make a concrete Lens for this spec that looks for an optional list of values in the target.`abstract fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<IN, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>?>` |
| [required](required.md) | Make a concrete Lens for this spec that looks for a required list of values in the target.`abstract fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](../-bi-di-lens/index.md)`<IN, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<OUT>>` |
