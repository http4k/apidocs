[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiPathLensSpec](./index.md)

# BiDiPathLensSpec

`open class BiDiPathLensSpec<OUT> : `[`PathLensSpec`](../-path-lens-spec/index.md)`<OUT>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BiDiPathLensSpec(paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OUT>, set: `[`LensSet`](../-lens-set/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, OUT>)` |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another BiDiPathLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a path segment.`fun <NEXT> map(nextIn: (OUT) -> NEXT, nextOut: (NEXT) -> OUT): `[`BiDiPathLensSpec`](./index.md)`<NEXT>` |
| [of](of.md) | Create a lens for this Spec`open fun of(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiPathLens`](../-bi-di-path-lens/index.md)`<OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [Path](../-path/index.md) | `object Path : `[`BiDiPathLensSpec`](./index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
