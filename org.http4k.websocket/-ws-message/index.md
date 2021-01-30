[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [WsMessage](./index.md)

# WsMessage

`data class WsMessage`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WsMessage(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>`WsMessage(value: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`)`<br>`WsMessage(body: `[`Body`](../../org.http4k.core/-body/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Body`](../../org.http4k.core/-body/index.md) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `fun body(new: `[`Body`](../../org.http4k.core/-body/index.md)`): `[`WsMessage`](./index.md) |
| [bodyString](body-string.md) | `fun bodyString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [binary](../../org.http4k.lens/binary.md) | `fun WsMessage.Companion.binary(): <ERROR CLASS>` |
| [string](../../org.http4k.lens/string.md) | `fun WsMessage.Companion.string(): <ERROR CLASS>` |
| [viewModel](../../org.http4k.template/view-model.md) | `fun WsMessage.Companion.viewModel(renderer: `[`TemplateRenderer`](../../org.http4k.template/-template-renderer.md)`): <ERROR CLASS>` |
