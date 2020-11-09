[http4k](../../index.md) / [org.http4k.format](../index.md) / [Argo](./index.md)

# Argo

`object Argo : `[`Json`](../-json/index.md)`<JsonNode>`

### Functions

| Name | Summary |
|---|---|
| [asCompactJsonString](as-compact-json-string.md) | `fun JsonNode.asCompactJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonArray](as-json-array.md) | `fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>> T.asJsonArray(): JsonNode` |
| [asJsonObject](as-json-object.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): JsonNode`<br>`fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, JsonNode>>> LIST.asJsonObject(): JsonNode` |
| [asJsonValue](as-json-value.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): JsonNode`<br>`fun `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): JsonNode`<br>`fun `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`?.asJsonValue(): JsonNode`<br>`fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): JsonNode` |
| [asPrettyJsonString](as-pretty-json-string.md) | `fun JsonNode.asPrettyJsonString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [bool](bool.md) | `fun bool(value: JsonNode): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [decimal](decimal.md) | `fun decimal(value: JsonNode): `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html) |
| [elements](elements.md) | `fun elements(value: JsonNode): `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<JsonNode>` |
| [fields](fields.md) | `fun fields(node: JsonNode): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, JsonNode!>>` |
| [integer](integer.md) | `fun integer(value: JsonNode): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [text](text.md) | `fun text(value: JsonNode): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [textValueOf](text-value-of.md) | `fun textValueOf(node: JsonNode, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [typeOf](type-of.md) | `fun typeOf(value: JsonNode): `[`JsonType`](../-json-type/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
| [haveBody](../../org.http4k.kotest/have-body.md) | `fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: NODE): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](../-json/index.md)`<NODE>.haveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`>` |
