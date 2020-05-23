[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](./index.md)

# WebsocketClient

`object WebsocketClient`

### Functions

| Name | Summary |
|---|---|
| [blocking](blocking.md) | Provides a client-side WsClient connected to a remote Websocket. This is a blocking API, so accessing the sequence of "received" messages will block on iteration until all messages are received (or the socket it closed). This call will also block while connection happens.`fun blocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO, autoReconnection: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`WsClient`](../../org.http4k.websocket/-ws-client/index.md) |
| [nonBlocking](non-blocking.md) | Provides a client-side Websocket instance connected to a remote Websocket. The resultant object can be have listeners attached to it. Optionally pass a WsConsumer which will be called onConnect`fun nonBlocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO, onError: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = {}, onConnect: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)` = {}): `[`Websocket`](../../org.http4k.websocket/-websocket/index.md) |
