[http4k](../../index.md) / [org.http4k.lens](../index.md) / [PathLensSpec](./index.md)

# PathLensSpec

`open class PathLensSpec<out OUT>`

Represents a uni-directional extraction of an entity from a target path segment.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a uni-directional extraction of an entity from a target path segment.`PathLensSpec(paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, OUT>)` |

### Properties

| Name | Summary |
|---|---|
| [paramMeta](param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another PathLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target path segment.`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`PathLensSpec`](./index.md)`<NEXT>` |
| [of](of.md) | `open fun of(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`PathLens`](../-path-lens/index.md)`<OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiPathLensSpec](../-bi-di-path-lens-spec/index.md) | `open class BiDiPathLensSpec<OUT> : `[`PathLensSpec`](./index.md)`<OUT>` |
