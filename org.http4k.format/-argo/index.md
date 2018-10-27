[http4k](../../index.md) / [org.http4k.format](../index.md) / [Argo](./index.md)

# Argo

`object Argo : `[`Json`](../-json/index.md)`<JsonNode>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-argo/src/main/kotlin/org/http4k/format/Argo.kt#L14)

### Functions

| Name | Summary |
|---|---|
| [asCompactJsonString](as-compact-json-string.md) | `fun JsonNode.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](as-json-array.md) | `fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>> `[`T`](as-json-array.md#T)`.asJsonArray(): JsonNode` |
| [asJsonObject](as-json-object.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): JsonNode`<br>`fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonNode>>> `[`LIST`](as-json-object.md#LIST)`.asJsonObject(): JsonNode` |
| [asJsonValue](as-json-value.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): JsonNode`<br>`fun `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): JsonNode` |
| [asPrettyJsonString](as-pretty-json-string.md) | `fun JsonNode.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [bool](bool.md) | `fun bool(value: JsonNode): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [elements](elements.md) | `fun elements(value: JsonNode): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>` |
| [fields](fields.md) | `fun fields(node: JsonNode): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonNode>>` |
| [text](text.md) | `fun text(value: JsonNode): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [textValueOf](text-value-of.md) | `fun textValueOf(node: JsonNode, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](type-of.md) | `fun typeOf(value: JsonNode): `[`JsonType`](../-json-type/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [array](../-json/array.md) | `open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`T`](../-json/array.md#T)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> array(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`T`](../-json/array.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [body](../-json/body.md) | `open fun body(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`NODE`](../-json/index.md#NODE)`>` |
| [boolean](../-json/boolean.md) | `open fun boolean(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [compact](../-json/compact.md) | `open fun compact(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [compactify](../-json/compactify.md) | `open fun compactify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [invoke](../-json/invoke.md) | `open operator fun <T> invoke(fn: `[`Json`](../-json/index.md)`<`[`NODE`](../-json/index.md#NODE)`>.() -> `[`T`](../-json/invoke.md#T)`): `[`T`](../-json/invoke.md#T) |
| [json](../-json/json.md) | `open fun <IN> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.json(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/json.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [lens](../-json/lens.md) | `open fun <IN> lens(spec: `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](../-json/lens.md#IN)`, `[`NODE`](../-json/index.md#NODE)`>` |
| [nullNode](../-json/null-node.md) | `open fun nullNode(): `[`NODE`](../-json/index.md#NODE) |
| [number](../-json/number.md) | `open fun number(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigDecimal`](http://docs.oracle.com/javase/6/docs/api/java/math/BigDecimal.html)`): `[`NODE`](../-json/index.md#NODE)<br>`open fun number(value: `[`BigInteger`](http://docs.oracle.com/javase/6/docs/api/java/math/BigInteger.html)`): `[`NODE`](../-json/index.md#NODE) |
| [obj](../-json/obj.md) | `open fun obj(): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(value: `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>>): `[`NODE`](../-json/index.md#NODE)<br>`open fun <T : `[`NODE`](../-json/index.md#NODE)`> obj(vararg fields: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`T`](../-json/obj.md#T)`>): `[`NODE`](../-json/index.md#NODE) |
| [parse](../-json/parse.md) | `open fun parse(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |
| [prettify](../-json/prettify.md) | `open fun prettify(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pretty](../-json/pretty.md) | `open fun pretty(node: `[`NODE`](../-json/index.md#NODE)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [string](../-json/string.md) | `open fun string(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`NODE`](../-json/index.md#NODE) |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<`[`NODE`](../../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
