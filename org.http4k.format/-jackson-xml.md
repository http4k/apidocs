[http4k](../index.md) / [org.http4k.format](index.md) / [JacksonXml](./-jackson-xml.md)

# JacksonXml

`object JacksonXml : `[`ConfigurableJacksonXml`](-configurable-jackson-xml/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson-xml/src/main/kotlin/org/http4k/format/JacksonXml.kt#L9)

To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called.

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](-configurable-jackson-xml/as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](-configurable-jackson-xml/as-a.md#T)`>): `[`T`](-configurable-jackson-xml/as-a.md#T) |
| [asXmlString](-configurable-jackson-xml/as-xml-string.md) | `open fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
