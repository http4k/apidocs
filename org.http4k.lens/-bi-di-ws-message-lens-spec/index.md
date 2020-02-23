[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiWsMessageLensSpec](./index.md)

# BiDiWsMessageLensSpec

`open class BiDiWsMessageLensSpec<OUT> : `[`WsMessageLensSpec`](../-ws-message-lens-spec/index.md)`<OUT>`

Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a bi-directional extraction of an entity from a target Body, or an insertion into a target WsMessage.`BiDiWsMessageLensSpec(get: `[`LensGet`](../-lens-get/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, OUT>, set: `[`LensSet`](../-lens-set/index.md)`<`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`, OUT>)` |

### Functions

| Name | Summary |
|---|---|
| [map](map.md) | Create another BiDiWsMessageLensSpec which applies the bi-directional transformations to the result. Any resultant Lens can be used to extract or insert the final type from/into a WsMessage.`fun <NEXT> map(nextIn: (OUT) -> NEXT, nextOut: (NEXT) -> OUT): `[`BiDiWsMessageLensSpec`](./index.md)`<NEXT>` |
| [toLens](to-lens.md) | Create a lens for this Spec`open fun toLens(): `[`BiDiWsMessageLens`](../-bi-di-ws-message-lens/index.md)`<OUT>` |
