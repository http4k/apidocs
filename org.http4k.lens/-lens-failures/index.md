[http4k](../../index.md) / [org.http4k.lens](../index.md) / [LensFailures](./index.md)

# LensFailures

`data class LensFailures : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/lens/Validator.kt#L31)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LensFailures(causes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensFailure`](../-lens-failure/index.md)`>)` |

### Properties

| Name | Summary |
|---|---|
| [causes](causes.md) | `val causes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LensFailure`](../-lens-failure/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
