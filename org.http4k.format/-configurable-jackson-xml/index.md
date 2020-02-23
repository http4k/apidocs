[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJacksonXml](./index.md)

# ConfigurableJacksonXml

`open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](../-auto-marshalling-xml/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableJacksonXml(mapper: XmlMapper)` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asXmlString](as-xml-string.md) | `open fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Inheritors

| Name | Summary |
|---|---|
| [JacksonXml](../-jackson-xml.md) | To implement custom XML configuration, create your own object singleton. Extra mappings can be added before done() is called.`object JacksonXml : `[`ConfigurableJacksonXml`](./index.md) |
