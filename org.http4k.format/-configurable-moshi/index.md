[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableMoshi](./index.md)

# ConfigurableMoshi

`open class ConfigurableMoshi : `[`AutoMarshallingJson`](../-auto-marshalling-json/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableMoshi(builder: Builder, defaultContentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)` = APPLICATION_JSON)` |

### Properties

| Name | Summary |
|---|---|
| [defaultContentType](default-content-type.md) | `val defaultContentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md) |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asFormatString](as-format-string.md) | `open fun asFormatString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [asJsonString](as-json-string.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asJsonString(t: T, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None, contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)` = defaultContentType): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<T>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<T>` |

### Inheritors

| Name | Summary |
|---|---|
| [Moshi](../-moshi.md) | To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called.`object Moshi : `[`ConfigurableMoshi`](./index.md) |
