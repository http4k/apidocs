[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJackson](index.md) / [asA](./as-a.md)

# asA

`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/ConfigurableJackson.kt#L63)

Overrides [AutoMarshallingJson.asA](../-auto-marshalling-json/as-a.md)


`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(j: `[`JsonNode`](https://fasterxml.github.io/jackson-databind/javadoc/2.10/com/fasterxml/jackson/databind/JsonNode.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/ConfigurableJackson.kt#L64)

Overrides [JsonLibAutoMarshallingJson.asA](../-json-lib-auto-marshalling-json/as-a.md)


`inline fun <reified T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`JsonNode`](https://fasterxml.github.io/jackson-databind/javadoc/2.10/com/fasterxml/jackson/databind/JsonNode.html)`.asA(): `[`T`](as-a.md#T) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson/src/main/kotlin/org/http4k/format/ConfigurableJackson.kt#L66)