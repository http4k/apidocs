[http4k](../index.md) / [org.http4k.lens](index.md) / [Cookies](./-cookies.md)

# Cookies

`object Cookies : `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`Request`](../org.http4k.core/-request/index.md)`, `[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/Cookies.kt#L9)

### Inherited Properties

| Name | Summary |
|---|---|
| [multi](-bi-di-lens-spec/multi.md) | `open val multi: `[`BiDiMultiLensSpec`](-bi-di-multi-lens-spec/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [defaulted](-bi-di-lens-spec/defaulted.md) | `open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`OUT`](-bi-di-lens-spec/index.md#OUT)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>`<br>Make a concrete Lens for this spec that falls back to the default value if no value is found in the target.`open fun defaulted(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, default: `[`Lens`](-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>`<br>Make a concrete Lens for this spec that falls back to another lens if no value is found in the target. |
| [map](-bi-di-lens-spec/map.md) | `fun <NEXT> map(nextIn: (`[`OUT`](-bi-di-lens-spec/index.md#OUT)`) -> `[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`, nextOut: (`[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`) -> `[`OUT`](-bi-di-lens-spec/index.md#OUT)`): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`NEXT`](-bi-di-lens-spec/map.md#NEXT)`>`<br>Create another BiDiLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a target. |
| [optional](-bi-di-lens-spec/optional.md) | `open fun optional(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`?>`<br>Make a concrete Lens for this spec that looks for an optional value in the target. |
| [required](-bi-di-lens-spec/required.md) | `open fun required(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`BiDiLens`](-bi-di-lens/index.md)`<`[`IN`](-bi-di-lens-spec/index.md#IN)`, `[`OUT`](-bi-di-lens-spec/index.md#OUT)`>`<br>Make a concrete Lens for this spec that looks for a required value in the target. |

### Extension Functions

| Name | Summary |
|---|---|
| [map](map.md) | `fun <NEXT, IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, OUT> `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](map.md#IN)`, `[`OUT`](map.md#OUT)`>.map(mapping: `[`BiDiMapping`](-bi-di-mapping/index.md)`<`[`OUT`](map.md#OUT)`, `[`NEXT`](map.md#NEXT)`>): `[`BiDiLensSpec`](-bi-di-lens-spec/index.md)`<`[`IN`](map.md#IN)`, `[`NEXT`](map.md#NEXT)`>` |
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
