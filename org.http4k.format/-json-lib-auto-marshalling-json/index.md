[http4k](../../index.md) / [org.http4k.format](../index.md) / [JsonLibAutoMarshallingJson](./index.md)

# JsonLibAutoMarshallingJson

`abstract class JsonLibAutoMarshallingJson<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`AutoMarshallingJson`](../-auto-marshalling-json/index.md)`, `[`Json`](../-json/index.md)`<`[`NODE`](index.md#NODE)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMarshallingJson.kt#L22)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonLibAutoMarshallingJson()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: `[`NODE`](index.md#NODE)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`NODE`](index.md#NODE)`.asA(): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`NODE`](index.md#NODE)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asJsonObject](as-json-object.md) | `abstract fun asJsonObject(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`NODE`](index.md#NODE)<br>`fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asJsonObject(): `[`NODE`](index.md#NODE) |
| [asJsonString](as-json-string.md) | `open fun asJsonString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [autoBody](auto-body.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> autoBody(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto-body.md#T)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [array](../-json/array.md) | `open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`T`](../-json/array.md#T)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`T`](../-json/array.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [asA](../-auto-marshalling-json/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-auto-marshalling-json/as-a.md#T)`>): `[`T`](../-auto-marshalling-json/as-a.md#T) |
| [asCompactJsonString](../-json/as-compact-json-string.md) | `abstract fun `[`NODE`](../-json/index.md#NODE)`.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asInputStream](../-auto-marshalling-json/as-input-stream.md) | `fun asInputStream(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`InputStream`](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) |
| [asJsonArray](../-json/as-json-array.md) | `abstract fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](../-json/index.md#NODE)`>> `[`T`](../-json/as-json-array.md#T)`.asJsonArray(): `[`NODE`](../-json/index.md#NODE) |
| [asJsonObject](../-json/as-json-object.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../-json/index.md#NODE)`>>> `[`LIST`](../-json/as-json-object.md#LIST)`.asJsonObject(): `[`NODE`](../-json/index.md#NODE) |
| [asJsonValue](../-json/as-json-value.md) | `abstract fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`BigDecimal`](https://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`BigInteger`](https://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE)<br>`abstract fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): `[`NODE`](../-json/index.md#NODE) |
| [asPrettyJsonString](../-json/as-pretty-json-string.md) | `abstract fun `[`NODE`](../-json/index.md#NODE)`.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [body](../-json/body.md) | `open fun body(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`NODE`](../-json/index.md#NODE)`>` |
| [bool](../-json/bool.md) | `abstract fun bool(value: `[`NODE`](../-json/index.md#NODE)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [boolean](../-json/boolean.md) | `open fun boolean(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [compact](../-json/compact.md) | `open fun compact(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [compactify](../-json/compactify.md) | `open fun compactify(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [elements](../-json/elements.md) | `abstract fun elements(value: `[`NODE`](../-json/index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](../-json/index.md#NODE)`>` |
| [fields](../-json/fields.md) | `abstract fun fields(node: `[`NODE`](../-json/index.md#NODE)`): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../-json/index.md#NODE)`>>` |
| [invoke](../-json/invoke.md) | `open operator fun <T> invoke(fn: `[`Json`](../-json/index.md)`<`[`NODE`](../-json/index.md#NODE)`>.() -> `[`T`](../-json/invoke.md#T)`): `[`T`](../-json/invoke.md#T) |
| [json](../-json/json.md) | `open fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.json(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [lens](../-json/lens.md) | `open fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> lens(spec: `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [nullNode](../-json/null-node.md) | `open fun nullNode(): `[`NODE`](../-json/index.md#NODE) |
| [number](../-json/number.md) | `open fun number(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigDecimal`](https://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigInteger`](https://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`): `[`NODE`](../-json/index.md#NODE) |
| [obj](../-json/obj.md) | `open fun obj(): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>>): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(vararg fields: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [parse](../-json/parse.md) | `open fun parse(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [prettify](../-json/prettify.md) | `open fun prettify(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pretty](../-json/pretty.md) | `open fun pretty(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [string](../-json/string.md) | `open fun string(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [text](../-json/text.md) | `abstract fun text(value: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [textValueOf](../-json/text-value-of.md) | `abstract fun textValueOf(node: `[`NODE`](../-json/index.md#NODE)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [typeOf](../-json/type-of.md) | `abstract fun typeOf(value: `[`NODE`](../-json/index.md#NODE)`): `[`JsonType`](../-json-type/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`T`](auto.md#T)`>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigurableGson](../-configurable-gson/index.md) | `open class ConfigurableGson : `[`JsonLibAutoMarshallingJson`](./index.md)`<JsonElement>` |
| [ConfigurableJackson](../-configurable-jackson/index.md) | `open class ConfigurableJackson : `[`JsonLibAutoMarshallingJson`](./index.md)`<JsonNode>` |
