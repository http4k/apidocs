[http4k](../../index.md) / [org.http4k.server](../index.md) / [Jetty](./index.md)

# Jetty

`class Jetty : `[`PolyServerConfig`](../-poly-server-config/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Jetty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)`<br>`Jetty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, vararg inConnectors: `[`ConnectorBuilder`](../-connector-builder.md)`)`<br>`Jetty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, server: Server)` |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?, ws: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`?, sse: `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`?): `[`Http4kServer`](../-http4k-server/index.md) |
