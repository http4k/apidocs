[http4k](../../index.md) / [org.http4k.server](../index.md) / [PolyHandler](./index.md)

# PolyHandler

`class PolyHandler`

A PolyHandler represents the combined routing logic of an multiple protocol handlers

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A PolyHandler represents the combined routing logic of an multiple protocol handlers`PolyHandler(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`? = null, ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`? = null, sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [http](http.md) | `val http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?` |
| [sse](sse.md) | `val sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`?` |
| [ws](ws.md) | `val ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [asServer](../as-server.md) | `fun `[`PolyHandler`](./index.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
| [testWsClient](../../org.http4k.testing/test-ws-client.md) | `fun `[`PolyHandler`](./index.md)`.testWsClient(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`TestWsClient`](../../org.http4k.testing/-test-ws-client/index.md)`?` |
