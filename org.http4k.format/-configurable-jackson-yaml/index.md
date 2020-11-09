[http4k](../../index.md) / [org.http4k.format](../index.md) / [ConfigurableJacksonYaml](./index.md)

# ConfigurableJacksonYaml

`open class ConfigurableJacksonYaml : `[`AutoMarshalling`](../-auto-marshalling/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigurableJacksonYaml(mapper: ObjectMapper)` |

### Properties

| Name | Summary |
|---|---|
| [mapper](mapper.md) | `val mapper: ObjectMapper` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asFormatString](as-format-string.md) | `open fun asFormatString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [autoBody](auto-body.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> autoBody(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<T>` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [auto](auto.md) | `fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> WsMessage.Companion.auto(): <ERROR CLASS>`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> Body.Companion.auto(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, contentNegotiation: `[`ContentNegotiation`](../../org.http4k.lens/-content-negotiation/index.md)` = None): `[`BiDiBodyLensSpec`](../../org.http4k.lens/-bi-di-body-lens-spec/index.md)`<T>` |

### Inheritors

| Name | Summary |
|---|---|
| [JacksonYaml](../-jackson-yaml.md) | `object JacksonYaml : `[`ConfigurableJacksonYaml`](./index.md) |
