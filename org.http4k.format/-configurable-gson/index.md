[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableGson](./index.md)

# ConfigurableGson

`open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](../-json-lib-auto-marshalling-json/index.md)`<JsonElement>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableGson(builder: GsonBuilder)` |

### Properties

| Name | Summary |
|---|---|
| [mapper](mapper.md) | `val mapper: Gson` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T`<br>`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: JsonElement, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> JsonElement.asA(): T` |
| [asCompactJsonString](as-compact-json-string.md) | `open fun JsonElement.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](as-json-array.md) | `open fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonElement>> T.asJsonArray(): JsonElement` |
| [asJsonObject](as-json-object.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): JsonElement`<br>`open fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonElement>>> LIST.asJsonObject(): JsonObject`<br>`open fun asJsonObject(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): JsonElement` |
| [asJsonValue](as-json-value.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`?.asJsonValue(): JsonElement`<br>`open fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): JsonElement` |
| [asPrettyJsonString](as-pretty-json-string.md) | `open fun JsonElement.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [autoBody](auto-body.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> autoBody(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<T>` |
| [bool](bool.md) | `open fun bool(value: JsonElement): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [decimal](decimal.md) | `open fun decimal(value: JsonElement): `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html) |
| [elements](elements.md) | `open fun elements(value: JsonElement): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonElement>` |
| [fields](fields.md) | `open fun fields(node: JsonElement): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonElement>>` |
| [integer](integer.md) | `open fun integer(value: JsonElement): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [text](text.md) | `open fun text(value: JsonElement): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [textValueOf](text-value-of.md) | `open fun textValueOf(node: JsonElement, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](type-of.md) | `open fun typeOf(value: JsonElement): `[`JsonType`](../-json-type/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<T>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<T>` |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
| [haveBody](../../org.http4k.kotest/have-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [Gson](../-gson.md) | To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.`object Gson : `[`ConfigurableGson`](./index.md) |
