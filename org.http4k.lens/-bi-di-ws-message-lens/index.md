[http4k](../../index.md) / [org.http4k.lens](../index.md) / [BiDiWsMessageLens](./index.md)

# BiDiWsMessageLens

`class BiDiWsMessageLens<FINAL> : `[`WsMessageLens`](../-ws-message-lens/index.md)`<FINAL>`

A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity
into a target WsMessage.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A BiDiWsMessageLens provides the bi-directional extraction of an entity from a target body, or the insertion of an entity into a target WsMessage.`BiDiWsMessageLens(get: (`[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> FINAL, setLens: (FINAL, `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`) -> `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `fun create(value: FINAL): `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md) |
| [invoke](invoke.md) | `operator fun invoke(target: FINAL): `[`WsMessage`](../../org.http4k.websocket/-ws-message/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [asResult](../as-result.md) | Convert the result of a lens extraction to a Result4k type which`fun <IN, OUT> `[`LensExtractor`](../-lens-extractor/index.md)`<IN, OUT>.asResult(): `[`LensExtractor`](../-lens-extractor/index.md)`<IN, Result<OUT, `[`LensFailure`](../-lens-failure/index.md)`>>` |
