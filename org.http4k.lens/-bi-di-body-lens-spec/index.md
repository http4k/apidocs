[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiBodyLensSpec](./index.md)

# BiDiBodyLensSpec

`open class BiDiBodyLensSpec<OUT> : `[`BodyLensSpec`](../-body-lens-spec/index.md)`<OUT>`

Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body.`BiDiBodyLensSpec(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, OUT>, set: `[`LensSet`](../-lens-set/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, OUT>)` |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another BiDiBodyLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a Body.`fun <NEXT> map(nextIn: (OUT) -> NEXT, nextOut: (NEXT) -> OUT): `[`BiDiBodyLensSpec`](./index.md)`<NEXT>` |
| [toLens](to-lens.md) | Create a lens for this Spec`open fun toLens(): `[`BiDiBodyLens`](../-bi-di-body-lens/index.md)`<OUT>` |
