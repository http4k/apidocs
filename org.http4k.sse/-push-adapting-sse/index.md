[http4k](../../index.md) / [org.http4k.sse](../index.md) / [PushAdaptingSse](./index.md)

# PushAdaptingSse

`abstract class PushAdaptingSse : `[`Sse`](../-sse/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PushAdaptingSse(connectRequest: `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [connectRequest](connect-request.md) | `open val connectRequest: `[`Request`](../../org.http4k.core/-request/index.md) |

### Functions

| Name | Summary |
|---|---|
| [onClose](on-close.md) | `open fun onClose(fn: () -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [triggerClose](trigger-close.md) | `fun triggerClose(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
