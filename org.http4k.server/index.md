[http4k](../index.md) / [org.http4k.server](./index.md)

## Package org.http4k.server

Common code relevant to HTTP server implementations.

### Types

| Name | Summary |
|---|---|
| [Apache4Server](-apache4-server/index.md) | `data class Apache4Server : `[`ServerConfig`](-server-config/index.md) |
| [ApacheServer](-apache-server/index.md) | `data class ApacheServer : `[`ServerConfig`](-server-config/index.md) |
| [ConnectorBuilder](-connector-builder.md) | `typealias ConnectorBuilder = (Server) -> ServerConnector` |
| [Http4kApache4RequestHandler](-http4k-apache4-request-handler/index.md) | Exposed to allow for insertion into a customised Apache WebServer instance`class Http4kApache4RequestHandler : HttpRequestHandler` |
| [Http4kChannelHandler](-http4k-channel-handler/index.md) | Exposed to allow for insertion into a customised Netty server instance`class Http4kChannelHandler : SimpleChannelInboundHandler<FullHttpRequest>` |
| [Http4kRequestHandler](-http4k-request-handler/index.md) | Exposed to allow for insertion into a customised Apache WebServer instance`class Http4kRequestHandler : HttpRequestHandler` |
| [Http4kServer](-http4k-server/index.md) | `interface Http4kServer : `[`AutoCloseable`](https://docs.oracle.com/javase/9/docs/api/java/lang/AutoCloseable.html) |
| [Http4kWebSocketListener](-http4k-web-socket-listener/index.md) | `class Http4kWebSocketListener : WebSocketListener` |
| [Http4kWsChannelHandler](-http4k-ws-channel-handler/index.md) | `class Http4kWsChannelHandler : SimpleChannelInboundHandler<WebSocketFrame>` |
| [HttpExchangeHandler](-http-exchange-handler/index.md) | `class HttpExchangeHandler : `[`HttpHandler`](https://docs.oracle.com/javase/9/docs/api/com/sun/net/httpserver/HttpHandler.html) |
| [HttpUndertowHandler](-http-undertow-handler/index.md) | Exposed to allow for insertion into a customised Undertow server instance`class HttpUndertowHandler : HttpHandler` |
| [Jetty](-jetty/index.md) | `class Jetty : `[`WsServerConfig`](-ws-server-config/index.md) |
| [KtorCIO](-ktor-c-i-o/index.md) | `data class KtorCIO : `[`ServerConfig`](-server-config/index.md) |
| [KtorNetty](-ktor-netty/index.md) | `data class KtorNetty : `[`ServerConfig`](-server-config/index.md) |
| [Netty](-netty/index.md) | `data class Netty : `[`WsServerConfig`](-ws-server-config/index.md) |
| [Ratpack](-ratpack/index.md) | `class Ratpack : `[`ServerConfig`](-server-config/index.md) |
| [RatpackHttp4kHandler](-ratpack-http4k-handler/index.md) | `class RatpackHttp4kHandler : Handler` |
| [ServerConfig](-server-config/index.md) | `interface ServerConfig` |
| [SunHttp](-sun-http/index.md) | `data class SunHttp : `[`ServerConfig`](-server-config/index.md) |
| [Undertow](-undertow/index.md) | `data class Undertow : `[`ServerConfig`](-server-config/index.md) |
| [WebSocketServerHandler](-web-socket-server-handler/index.md) | `class WebSocketServerHandler : ChannelInboundHandlerAdapter` |
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
| [&lt;no name provided&gt;](-no name provided-.md) | Standard interface for creating a configured WebServer`fun <no name provided>(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [asServer](as-server.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.asServer(config: `[`WsServerConfig`](-ws-server-config/index.md)`): `[`Http4kServer`](-http4k-server/index.md) |
| [http](http.md) | `fun http(httpPort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
| [http2](http2.md) | `fun http2(http2Port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, keystorePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, keystorePassword: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`ConnectorBuilder`](-connector-builder.md) |
