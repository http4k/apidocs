[http4k](../index.md) / [org.http4k.format](index.md) / [KotlinxSerialization](./-kotlinx-serialization.md)

# KotlinxSerialization

`object KotlinxSerialization : `[`ConfigurableKotlinxSerialization`](-configurable-kotlinx-serialization/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-kotlinx-serialization/src/main/kotlin/org/http4k/format/KotlinxSerialization.kt#L10)

To implement custom JSON configuration, create your own object singleton extending
ConfigurableKotlinxSerialization.

### Inherited Functions

| Name | Summary |
|---|---|
| [asCompactJsonString](-configurable-kotlinx-serialization/as-compact-json-string.md) | `open fun <ERROR CLASS>.asCompactJsonString(): <ERROR CLASS>` |
| [asJsonArray](-configurable-kotlinx-serialization/as-json-array.md) | `open fun <T : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<<ERROR CLASS>>> `[`T`](-configurable-kotlinx-serialization/as-json-array.md#T)`.asJsonArray(): <ERROR CLASS>` |
| [asJsonObject](-configurable-kotlinx-serialization/as-json-object.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asJsonObject(): <ERROR CLASS>`<br>`open fun <LIST : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, <ERROR CLASS>>>> `[`LIST`](-configurable-kotlinx-serialization/as-json-object.md#LIST)`.asJsonObject(): <ERROR CLASS>` |
| [asJsonValue](-configurable-kotlinx-serialization/as-json-value.md) | `open fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`BigInteger`](https://docs.oracle.com/javase/9/docs/api/java/math/BigInteger.html)`?.asJsonValue(): <ERROR CLASS>`<br>`open fun `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?.asJsonValue(): <ERROR CLASS>` |
| [asPrettyJsonString](-configurable-kotlinx-serialization/as-pretty-json-string.md) | `open fun <ERROR CLASS>.asPrettyJsonString(): <ERROR CLASS>` |
| [bool](-configurable-kotlinx-serialization/bool.md) | `open fun bool(value: <ERROR CLASS>): <ERROR CLASS>` |
| [decimal](-configurable-kotlinx-serialization/decimal.md) | `open fun decimal(value: <ERROR CLASS>): `[`BigDecimal`](https://docs.oracle.com/javase/9/docs/api/java/math/BigDecimal.html) |
| [elements](-configurable-kotlinx-serialization/elements.md) | `open fun elements(value: <ERROR CLASS>): <ERROR CLASS>` |
| [fields](-configurable-kotlinx-serialization/fields.md) | `open fun fields(node: <ERROR CLASS>): <ERROR CLASS>` |
| [integer](-configurable-kotlinx-serialization/integer.md) | `open fun integer(value: <ERROR CLASS>): <ERROR CLASS>` |
| [text](-configurable-kotlinx-serialization/text.md) | `open fun text(value: <ERROR CLASS>): <ERROR CLASS>` |
| [textValueOf](-configurable-kotlinx-serialization/text-value-of.md) | `open fun textValueOf(node: <ERROR CLASS>, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html) |
| [typeOf](-configurable-kotlinx-serialization/type-of.md) | `open fun typeOf(value: <ERROR CLASS>): `[`JsonType`](-json-type/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](-json/index.md)`<`[`NODE`](../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`NODE`](../org.http4k.hamkrest/has-body.md#NODE)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<`[`NODE`](../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: Matcher<`[`NODE`](../org.http4k.hamkrest/has-body.md#NODE)`>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<`[`NODE`](../org.http4k.hamkrest/has-body.md#NODE)`>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>` |
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
