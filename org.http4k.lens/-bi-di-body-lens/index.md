[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLens](./index.md)

# BiDiBodyLens

`class BiDiBodyLens<FINAL> : `[`LensInjector`](../-lens-injector/index.md)`<FINAL, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>, `[`BodyLens`](../-body-lens/index.md)`<FINAL>`

A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A BiDiBodyLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target body.`BiDiBodyLens(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: (`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> FINAL, setLens: (FINAL, `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`) -> `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to set the value into the target`operator fun <R : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(value: FINAL, target: R): R` |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |
