[http4k](../../index.md) / [org.http4k.server](../index.md) / [PolyServerConfig](./index.md)

# PolyServerConfig

`interface PolyServerConfig : `[`ServerConfig`](../-server-config/index.md)

Standard interface for creating a configured WebServer which supports Websockets

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `open fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md)<br>`abstract fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`? = null, ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`? = null, sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`? = null): `[`Http4kServer`](../-http4k-server/index.md) |
| [toSseServer](to-sse-server.md) | `open fun toSseServer(sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
| [toWsServer](to-ws-server.md) | `open fun toWsServer(ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Jetty](../-jetty/index.md) | `class Jetty : `[`PolyServerConfig`](./index.md) |
| [Netty](../-netty/index.md) | `data class Netty : `[`PolyServerConfig`](./index.md) |
| [Undertow](../-undertow/index.md) | `data class Undertow : `[`PolyServerConfig`](./index.md) |
