[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableKotlinxSerialization](./index.md)

# ConfigurableKotlinxSerialization

`open class ConfigurableKotlinxSerialization : `[`Json`](../-json/index.md)`<<ERROR CLASS>>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-kotlinx-serialization/src/main/kotlin/org/http4k/format/ConfigurableKotlinxSerialization.kt#L19)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableKotlinxSerialization(config: <ERROR CLASS>, context: <ERROR CLASS>)` |

### Functions

| Name | Summary |
|---|---|
| [asCompactJsonString](as-compact-json-string.md) | `open fun <ERROR CLASS>.asCompactJsonString(): <ERROR CLASS>` |
| [asJsonArray](as-json-array.md) | `open fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<<ERROR CLASS>>> `[`T`](as-json-array.md#T)`.asJsonArray(): <ERROR CLASS>` |
| [asJsonObject](as-json-object.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): <ERROR CLASS>`<br>`open fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, <ERROR CLASS>>>> `[`LIST`](as-json-object.md#LIST)`.asJsonObject(): <ERROR CLASS>` |
| [asJsonValue](as-json-value.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): <ERROR CLASS>` |
| [asPrettyJsonString](as-pretty-json-string.md) | `open fun <ERROR CLASS>.asPrettyJsonString(): <ERROR CLASS>` |
| [bool](bool.md) | `open fun bool(value: <ERROR CLASS>): <ERROR CLASS>` |
| [decimal](decimal.md) | `open fun decimal(value: <ERROR CLASS>): `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html) |
| [elements](elements.md) | `open fun elements(value: <ERROR CLASS>): <ERROR CLASS>` |
| [fields](fields.md) | `open fun fields(node: <ERROR CLASS>): <ERROR CLASS>` |
| [integer](integer.md) | `open fun integer(value: <ERROR CLASS>): <ERROR CLASS>` |
| [text](text.md) | `open fun text(value: <ERROR CLASS>): <ERROR CLASS>` |
| [textValueOf](text-value-of.md) | `open fun textValueOf(node: <ERROR CLASS>, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html) |
| [typeOf](type-of.md) | `open fun typeOf(value: <ERROR CLASS>): `[`JsonType`](../-json-type/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [array](../-json/array.md) | `open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`T`](../-json/array.md#T)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`T`](../-json/array.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [asJsonArray](../-json/as-json-array.md) | `abstract fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`NODE`](../-json/index.md#NODE)`>> `[`T`](../-json/as-json-array.md#T)`.asJsonArray(): `[`NODE`](../-json/index.md#NODE) |
| [asJsonObject](../-json/as-json-object.md) | `abstract fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`NODE`](../-json/index.md#NODE)`>>> `[`LIST`](../-json/as-json-object.md#LIST)`.asJsonObject(): `[`NODE`](../-json/index.md#NODE) |
| [body](../-json/body.md) | `open fun body(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`NODE`](../-json/index.md#NODE)`>` |
| [boolean](../-json/boolean.md) | `open fun boolean(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [compact](../-json/compact.md) | `open fun compact(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [compactify](../-json/compactify.md) | `open fun compactify(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [invoke](../-json/invoke.md) | `open operator fun <T> invoke(fn: `[`Json`](../-json/index.md)`<`[`NODE`](../-json/index.md#NODE)`>.() -> `[`T`](../-json/invoke.md#T)`): `[`T`](../-json/invoke.md#T) |
| [json](../-json/json.md) | `open fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.json(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [lens](../-json/lens.md) | `open fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> lens(spec: `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [nullNode](../-json/null-node.md) | `open fun nullNode(): `[`NODE`](../-json/index.md#NODE) |
| [number](../-json/number.md) | `open fun number(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`): `[`NODE`](../-json/index.md#NODE) |
| [obj](../-json/obj.md) | `open fun obj(): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>>): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(vararg fields: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [parse](../-json/parse.md) | `open fun parse(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [prettify](../-json/prettify.md) | `open fun prettify(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pretty](../-json/pretty.md) | `open fun pretty(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [string](../-json/string.md) | `open fun string(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [KotlinxSerialization](../-kotlinx-serialization.md) | `object KotlinxSerialization : `[`ConfigurableKotlinxSerialization`](./index.md)<br>To implement custom JSON configuration, create your own object singleton extending ConfigurableKotlinxSerialization. |
