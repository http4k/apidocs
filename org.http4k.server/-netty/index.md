[http4k](../../index.md) / [org.http4k.server](../index.md) / [Netty](./index.md)

# Netty

`data class Netty : `[`WsServerConfig`](../-ws-server-config/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Netty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)` |

### Properties

| Name | Summary |
|---|---|
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?, wsHandler: `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`?): `[`Http4kServer`](../-http4k-server/index.md) |
