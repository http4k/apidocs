[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kWsChannelHandler](./index.md)

# Http4kWsChannelHandler

`class Http4kWsChannelHandler : SimpleChannelInboundHandler<WebSocketFrame>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kWsChannelHandler(wSocket: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)`, upgradeRequest: `[`Request`](../../org.http4k.core/-request/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [channelRead0](channel-read0.md) | `fun channelRead0(ctx: ChannelHandlerContext, msg: WebSocketFrame): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [exceptionCaught](exception-caught.md) | `fun exceptionCaught(ctx: ChannelHandlerContext, cause: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [handlerAdded](handler-added.md) | `fun handlerAdded(ctx: ChannelHandlerContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [handlerRemoved](handler-removed.md) | `fun handlerRemoved(ctx: ChannelHandlerContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
