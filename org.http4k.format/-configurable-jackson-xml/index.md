[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJacksonXml](./index.md)

# ConfigurableJacksonXml

`open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](../-auto-marshalling-xml/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-jackson-xml/src/main/kotlin/org/http4k/format/ConfgurableJacksonXml.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableJacksonXml(mapper: XmlMapper)` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asXmlString](as-xml-string.md) | `open fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](../-auto-marshalling-xml/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](../-auto-marshalling-xml/as-a.md#T)<br>`abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-auto-marshalling-xml/as-a.md#T)`>): `[`T`](../-auto-marshalling-xml/as-a.md#T) |
| [asXmlString](../-auto-marshalling-xml/as-xml-string.md) | `fun asXmlString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [JacksonXml](../-jackson-xml.md) | `object JacksonXml : `[`ConfigurableJacksonXml`](./index.md)<br>To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called. |
