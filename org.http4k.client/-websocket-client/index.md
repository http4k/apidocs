[http4k](../../index.md) / [org.http4k.client](../index.md) / [WebsocketClient](./index.md)

# WebsocketClient

`object WebsocketClient` [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-websocket/src/main/kotlin/org/http4k/client/WebsocketClient.kt#L25)

### Functions

| Name | Summary |
|---|---|
| [blocking](blocking.md) | `fun blocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO): `[`WsClient`](../../org.http4k.websocket/-ws-client/index.md)<br>Provides a client-side WsClient connected to a remote Websocket. This is a blocking API, so accessing the sequence of "received" messages will block on iteration until all messages are received (or the socket it closed). This call will also block while connection happens. |
| [nonBlocking](non-blocking.md) | `fun nonBlocking(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, headers: `[`Headers`](../../org.http4k.core/-headers.md)` = emptyList(), timeout: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ZERO, onConnect: `[`WsConsumer`](../../org.http4k.websocket/-ws-consumer.md)` = {}): `[`Websocket`](../../org.http4k.websocket/-websocket/index.md)<br>Provides a client-side Websocket instance connected to a remote Websocket. The resultant object can be have listeners attached to it. Optionally pass a WsConsumer which will be called onConnect |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
