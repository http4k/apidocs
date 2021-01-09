[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMarshallingJson](./index.md)

# AutoMarshallingJson

`abstract class AutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshalling`](../-auto-marshalling/index.md)`, `[`Json`](../-json/index.md)`<NODE>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoMarshallingJson()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: NODE, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> NODE.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asFormatString](as-format-string.md) | `open fun asFormatString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonObject](as-json-object.md) | `abstract fun asJsonObject(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): NODE`<br>`fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asJsonObject(): NODE` |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
| [haveBody](../../org.http4k.kotest/have-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigurableGson](../-configurable-gson/index.md) | `open class ConfigurableGson : `[`AutoMarshallingJson`](./index.md)`<JsonElement>` |
| [ConfigurableJackson](../-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`AutoMarshallingJson`](./index.md)`<JsonNode>` |
| [ConfigurableKotlinxSerialization](../-configurable-kotlinx-serialization/index.md) | `open class ConfigurableKotlinxSerialization : `[`AutoMarshallingJson`](./index.md)`<JsonElement>` |
