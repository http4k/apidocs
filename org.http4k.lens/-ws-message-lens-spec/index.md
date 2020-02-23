[http4k](../../index.md) / [org.http4k.lens](../index.md) / [WsMessageLensSpec](./index.md)

# WsMessageLensSpec

`open class WsMessageLensSpec<out OUT>`

Represents a extraction of an entity from a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a extraction of an entity from a target WsMessage.`WsMessageLensSpec(get: `[`LensGet`](../-lens-get/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, OUT>)` |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another WsMessageLensSpec which applies the uni-directional transformation to the result. Any resultant Lens can only be used to extract the final type from a WsMessage.`fun <NEXT> map(nextIn: (OUT) -> NEXT): `[`WsMessageLensSpec`](./index.md)`<NEXT>` |
| [toLens](to-lens.md) | Create a lens for this Spec`open fun toLens(): `[`WsMessageLens`](../-ws-message-lens/index.md)`<OUT>` |

### Inheritors

| Name | Summary |
|---|---|
| [BiDiWsMessageLensSpec](../-bi-di-ws-message-lens-spec/index.md) | Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage.`open class BiDiWsMessageLensSpec<OUT> : `[`WsMessageLensSpec`](./index.md)`<OUT>` |
