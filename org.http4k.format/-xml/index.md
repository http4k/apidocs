[http4k](../../index.md) / [org.http4k.format](../index.md) / [Xml](./index.md)

# Xml

`object Xml : `[`AutoMarshallingXml`](../-auto-marshalling-xml/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-xml/src/main/kotlin/org/http4k/format/Xml.kt#L24)

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T) |
| [asXmlDocument](as-xml-document.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asXmlDocument(): `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html) |
| [asXmlString](as-xml-string.md) | `fun `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>`fun `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`.asXmlString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asXmlToJsonElement](as-xml-to-json-element.md) | `fun `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asXmlToJsonElement(): JsonElement` |
| [xml](xml.md) | `fun <IN : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](xml.md#IN)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>.xml(): `[`BiDiLensSpec`](../../org.http4k.lens/-bi-di-lens-spec/index.md)`<`[`IN`](xml.md#IN)`, `[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`>` |

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](../-auto-marshalling-xml/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](../-auto-marshalling-xml/as-a.md#T)<br>`abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-auto-marshalling-xml/as-a.md#T)`>): `[`T`](../-auto-marshalling-xml/as-a.md#T) |
| [asXmlString](../-auto-marshalling-xml/as-xml-string.md) | `fun asXmlString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [xml](xml.md) | `fun Body.Companion.xml(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`Document`](https://kotlinlang.org/api/latest/jvm/stdlib/org.w3c.dom/-document/index.html)`>` |
