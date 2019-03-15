[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMarshallingXml](./index.md)

# AutoMarshallingXml

`abstract class AutoMarshallingXml` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/format/AutoMarshallingXml.kt#L16)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoMarshallingXml()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](as-a.md#T)<br>`abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asXmlString](as-xml-string.md) | `abstract fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>`fun asXmlString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto.md#T)`>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`T`](auto.md#T)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [ConfigurableJacksonXml](../-configurable-jackson-xml/index.md) | `open class ConfigurableJacksonXml : `[`AutoMarshallingXml`](./index.md) |
| [Xml](../-xml/index.md) | `object Xml : `[`AutoMarshallingXml`](./index.md) |
