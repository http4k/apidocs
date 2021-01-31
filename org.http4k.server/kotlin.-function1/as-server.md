[http4k](../../index.md) / [org.http4k.server](../index.md) / [kotlin.Function1](index.md) / [asServer](./as-server.md)

# asServer

`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(fn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../-server-config/index.md)`, port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)
`@JvmName("wsConsumerAsServer") fun `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)
`@JvmName("sseConsumerAsServer") fun `[`SseConsumer`](../../org.http4k.sse/-sse-consumer.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)
`fun `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`.asServer(config: `[`ServerConfig`](../-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)
`@JvmName("sseHandlerAsServer") fun `[`SseHandler`](../../org.http4k.sse/-sse-handler.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)
`@JvmName("wsHandlerAsServer") fun `[`WsHandler`](../../org.http4k.websocket/-ws-handler.md)`.asServer(config: `[`PolyServerConfig`](../-poly-server-config/index.md)`): `[`Http4kServer`](../-http4k-server/index.md)