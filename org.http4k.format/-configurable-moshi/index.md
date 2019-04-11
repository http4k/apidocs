[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableMoshi](./index.md)

# ConfigurableMoshi

`open class ConfigurableMoshi : `[`AutoMarshallingJson`](../-auto-marshalling-json/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-format-moshi/src/main/kotlin/org/http4k/format/internalMoshi.kt#L20)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableMoshi(builder: Builder)` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-a.md#T)`>): `[`T`](as-a.md#T)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(s: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](as-a.md#T) |
| [asJsonString](as-json-string.md) | `open fun asJsonString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asJsonString(t: `[`T`](as-json-string.md#T)`, c: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](as-json-string.md#T)`>): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [asA](../-auto-marshalling-json/as-a.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<`[`T`](../-auto-marshalling-json/as-a.md#T)`>): `[`T`](../-auto-marshalling-json/as-a.md#T) |
| [asInputStream](../-auto-marshalling-json/as-input-stream.md) | `fun asInputStream(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`InputStream`](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = ContentNegotiation.None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<`[`T`](auto.md#T)`>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): `[`BiDiWsMessageLensSpec`](../../org.http4k.lens/-bi-di-ws-message-lens-spec/index.md)`<`[`T`](auto.md#T)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [Moshi](../-moshi.md) | `object Moshi : `[`ConfigurableMoshi`](./index.md)<br>To implement custom JSON configuration, create your own object singleton. Extra mappings can be added before done() is called. |
