[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WebForm](./index.md)

# WebForm

`data class WebForm`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WebForm(fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>> = emptyMap(), errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`> = emptyList())` |

### Properties

| Name | Summary |
|---|---|
| [errors](errors.md) | `val errors: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Failure`](../-failure/index.md)`>` |
| [fields](fields.md) | `val fields: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>` |

### Functions

| Name | Summary |
|---|---|
| [minus](minus.md) | `operator fun minus(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`WebForm`](./index.md) |
| [plus](plus.md) | `operator fun plus(kv: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`WebForm`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun `[`WebForm`](./index.md)`.with(vararg modifiers: (`[`WebForm`](./index.md)`) -> `[`WebForm`](./index.md)`): `[`WebForm`](./index.md) |
