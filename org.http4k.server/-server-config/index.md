[http4k](../../index.md) / [org.http4k.server](../index.md) / [ServerConfig](./index.md)

# ServerConfig

`interface ServerConfig`

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `abstract fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Apache4Server](../-apache4-server/index.md) | `data class Apache4Server : `[`ServerConfig`](./index.md) |
| [ApacheServer](../-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](./index.md) |
| [KtorCIO](../-ktor-c-i-o/index.md) | `data class KtorCIO : `[`ServerConfig`](./index.md) |
| [KtorNetty](../-ktor-netty/index.md) | `data class KtorNetty : `[`ServerConfig`](./index.md) |
| [PolyServerConfig](../-poly-server-config/index.md) | Standard interface for creating a configured WebServer which supports Websockets`interface PolyServerConfig : `[`ServerConfig`](./index.md) |
| [Ratpack](../-ratpack/index.md) | `class Ratpack : `[`ServerConfig`](./index.md) |
| [SunHttp](../-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](./index.md) |
