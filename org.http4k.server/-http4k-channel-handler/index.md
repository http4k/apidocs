[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kChannelHandler](./index.md)

# Http4kChannelHandler

`class Http4kChannelHandler : `[`SimpleChannelInboundHandler`](https://netty.io/4.1/api/io/netty/channel/SimpleChannelInboundHandler.html)`<`[`FullHttpRequest`](https://netty.io/4.1/api/io/netty/handler/codec/http/FullHttpRequest.html)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-server-netty/src/main/kotlin/org/http4k/server/Netty.kt#L42)

Exposed to allow for insertion into a customised Netty server instance

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kChannelHandler(handler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>Exposed to allow for insertion into a customised Netty server instance |

### Functions

| Name | Summary |
|---|---|
| [channelRead0](channel-read0.md) | `fun channelRead0(ctx: `[`ChannelHandlerContext`](https://netty.io/4.1/api/io/netty/channel/ChannelHandlerContext.html)`, request: `[`FullHttpRequest`](https://netty.io/4.1/api/io/netty/handler/codec/http/FullHttpRequest.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
