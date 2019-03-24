[http4k](../index.md) / [org.http4k.format](index.md) / [Moshi](./-moshi.md)

# Moshi

`object Moshi : `[`ConfigurableMoshi`](-configurable-moshi/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-moshi/src/main/kotlin/org/http4k/format/Moshi.kt#L8)

To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](-configurable-moshi/as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](-configurable-moshi/as-a.md#T)`>): `[`T`](-configurable-moshi/as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](-configurable-moshi/as-a.md#T) |
| [asJsonString](-configurable-moshi/as-json-string.md) | `open fun asJsonString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asJsonString(t: `[`T`](-configurable-moshi/as-json-string.md#T)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](-configurable-moshi/as-json-string.md#T)`>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
