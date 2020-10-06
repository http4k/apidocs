[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLens](./index.md)

# BodyLens

`open class BodyLens<out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, FINAL>`

A BodyLens provides the uni-directional extraction of an entity from a target body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A BodyLens provides the uni-directional extraction of an entity from a target body.`BodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, getLens: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> FINAL)` |

### Properties

| Name | Summary |
|---|---|
| [contentType](content-type.md) | `val contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |
| [metas](metas.md) | `val metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to get the value from the target`open operator fun invoke(target: `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`): FINAL` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLens](../-bi-di-body-lens/index.md) | A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body.`class BiDiBodyLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](./index.md)`<FINAL>` |
