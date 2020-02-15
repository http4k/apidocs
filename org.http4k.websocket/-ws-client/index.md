[http4k](../../index.md) / [org.http4k.websocket](../index.md) / [WsClient](./index.md)

# WsClient

`interface WsClient` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/websocket/WsClient.kt#L5)

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `abstract fun close(status: `[`WsStatus`](../-ws-status/index.md)` = NORMAL): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [received](received.md) | `abstract fun received(): `[`Sequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.sequences/-sequence/index.html)`<`[`WsMessage`](../-ws-message/index.md)`>` |
| [send](send.md) | `abstract fun send(message: `[`WsMessage`](../-ws-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [TestWsClient](../../org.http4k.testing/-test-ws-client/index.md) | `class TestWsClient : `[`WsClient`](./index.md)<br>A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls are routed synchronously to the receiving Websocket, and error are propagated to the caller. |
