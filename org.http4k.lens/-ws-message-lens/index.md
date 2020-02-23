[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLens](./index.md)

# WsMessageLens

`open class WsMessageLens<out FINAL> : `[`LensExtractor`](../-lens-extractor/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, FINAL>`

A WsMessageLens provides the extraction of an entity from a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A WsMessageLens provides the extraction of an entity from a target WsMessage.`WsMessageLens(getLens: (`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> FINAL)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to get the value from the target`open operator fun invoke(target: `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`): FINAL` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiWsMessageLens](../-bi-di-ws-message-lens/index.md) | A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target WsMessage.`class BiDiWsMessageLens<FINAL> : `[`WsMessageLens`](./index.md)`<FINAL>` |
