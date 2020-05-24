[http4k](../../index.md) / [org.http4k.server](../index.md) / [ServerConfig](./index.md)

# ServerConfig

`interface ServerConfig`

Standard interface for creating a configured WebServer

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `abstract fun toServer(httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [ApacheServer](../-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](./index.md) |
| [KtorCIO](../-ktor-c-i-o/index.md) | `data class KtorCIO : `[`ServerConfig`](./index.md) |
| [KtorNetty](../-ktor-netty/index.md) | `data class KtorNetty : `[`ServerConfig`](./index.md) |
| [Netty](../-netty/index.md) | `data class Netty : `[`ServerConfig`](./index.md) |
| [Ratpack](../-ratpack/index.md) | `class Ratpack : `[`ServerConfig`](./index.md) |
| [SunHttp](../-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](./index.md) |
| [Undertow](../-undertow/index.md) | `data class Undertow : `[`ServerConfig`](./index.md) |
| [WsServerConfig](../-ws-server-config/index.md) | Standard interface for creating a configured WebServer which supports Websockets`interface WsServerConfig : `[`ServerConfig`](./index.md) |
