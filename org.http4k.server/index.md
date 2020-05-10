[http4k](../index.md) / [org.http4k.server](./index.md)

## Package org.http4k.server

Common code relevant to HTTP server implementations.

### Types

| Name | Summary |
|---|---|
| [ApacheServer](-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](-server-config/index.md) |
| [ConnectorBuilder](-connector-builder.md) | `typealias ConnectorBuilder = (Server) -> ServerConnector` |
| [Http4kChannelHandler](-http4k-channel-handler/index.md) | Exposed to allow for insertion into a customised Netty server instance`class Http4kChannelHandler : SimpleChannelInboundHandler<FullHttpRequest>` |
| [Http4kRequestHandler](-http4k-request-handler/index.md) | Exposed to allow for insertion into a customised Apache WebServer instance`class Http4kRequestHandler : HttpRequestHandler` |
| [Http4kServer](-http4k-server/index.md) | `interface Http4kServer : `[`AutoCloseable`](https://docs.oracle.com/javase/9/docs/api/java/lang/AutoCloseable.html) |
| [Http4kWebSocketAdapter](-http4k-web-socket-adapter/index.md) | `class Http4kWebSocketAdapter` |
| [Http4kWebSocketListener](-http4k-web-socket-listener/index.md) | `class Http4kWebSocketListener : WebSocketListener` |
| [HttpUndertowHandler](-http-undertow-handler/index.md) | Exposed to allow for insertion into a customised Undertow server instance`class HttpUndertowHandler : HttpHandler` |
| [Jetty](-jetty/index.md) | `class Jetty : `[`WsServerConfig`](-ws-server-config/index.md) |
| [KtorCIO](-ktor-c-i-o/index.md) | `data class KtorCIO : `[`ServerConfig`](-server-config/index.md) |
| [KtorNetty](-ktor-netty/index.md) | `data class KtorNetty : `[`ServerConfig`](-server-config/index.md) |
| [Netty](-netty/index.md) | `data class Netty : `[`ServerConfig`](-server-config/index.md) |
| [ServerConfig](-server-config/index.md) | Standard interface for creating a configured WebServer`interface ServerConfig` |
| [SunHttp](-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](-server-config/index.md) |
| [Undertow](-undertow/index.md) | `data class Undertow : `[`ServerConfig`](-server-config/index.md) |
| [WsServerConfig](-ws-server-config/index.md) | Standard interface for creating a configured WebServer which supports Websockets`interface WsServerConfig : `[`ServerConfig`](-server-config/index.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [io.ktor.request.ApplicationRequest](io.ktor.request.-application-request/index.md) |  |
| [io.ktor.response.ApplicationResponse](io.ktor.response.-application-response/index.md) |  |
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [asServer](as-server.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.asServer(config: `[`WsServerConfig`](-ws-server-config/index.md)`): `[`Http4kServer`](-http4k-server/index.md) |
| [http](http.md) | `fun http(httpPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
| [http2](http2.md) | `fun http2(http2Port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, keystorePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, keystorePassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
