[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BodyLensSpec](./index.md)

# BodyLensSpec

`open class BodyLensSpec<out OUT>`

Represents a uni-directional extraction of an entity from a target Body.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a uni-directional extraction of an entity from a target Body.`BodyLensSpec(metas: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Meta`](../-meta/index.md)`>, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`, OUT>)` |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another BodyLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a Body.`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`BodyLensSpec`](./index.md)`<NEXT>` |
| [toLens](to-lens.md) | Create a lens for this Spec`open fun toLens(): `[`BodyLens`](../-body-lens/index.md)`<OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiBodyLensSpec](../-bi-di-body-lens-spec/index.md) | Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target Body.`open class BiDiBodyLensSpec<OUT> : `[`BodyLensSpec`](./index.md)`<OUT>` |
