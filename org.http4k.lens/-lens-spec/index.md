[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensSpec](./index.md)

# LensSpec

`open class LensSpec<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT>`

Represents a uni-directional extraction of an entity from a target.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a uni-directional extraction of an entity from a target.`LensSpec(location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paramMeta: `[`ParamMeta`](../-param-meta/index.md)`, get: `[`LensGet`](../-lens-get/index.md)`<IN, OUT>)` |

### Properties

| Name | Summary |
|---|---|
| [location](location.md) | `val location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [multi](multi.md) | `open val multi: `[`MultiLensSpec`](../-multi-lens-spec/index.md)`<IN, OUT>` |
| [paramMeta](param-meta.md) | `val paramMeta: `[`ParamMeta`](../-param-meta/index.md) |

### Functions

| Name | Summary |
|---|---|
| [defaulted](defaulted.md) | Make a concrete Lens for this spec that falls back to the default value if no value is found in the target.`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: OUT, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT>`<br>Make a concrete Lens for this spec that falls back to another lens if no value is found in the target.`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](../-lens/index.md)`<IN, OUT>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT>` |
| [map](map.md) | Create another LensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a target.`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`LensSpec`](./index.md)`<IN, NEXT>` |
| [optional](optional.md) | Make a concrete Lens for this spec that looks for an optional value in the target.`open fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT?>` |
| [required](required.md) | Make a concrete Lens for this spec that looks for a required value in the target.`open fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Lens`](../-lens/index.md)`<IN, OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiLensSpec](../-bi-di-lens-spec/index.md) | Represents a bi-directional extraction of an entity from a target, or an insertion into a target.`open class BiDiLensSpec<IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> : `[`LensSpec`](./index.md)`<IN, OUT>` |
