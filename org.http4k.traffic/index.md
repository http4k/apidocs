[http4k](../index.md) / [org.http4k.traffic](./index.md)

## Package org.http4k.traffic

### Types

| Name | Summary |
|---|---|
| [ReadWriteCache](-read-write-cache/index.md) | Combined Read/Write storage models, optimised for retrieval.`interface ReadWriteCache : `[`Sink`](-sink/index.md)`, `[`Source`](-source/index.md) |
| [ReadWriteStream](-read-write-stream/index.md) | Combined Read/Write storage models, optimised for replay.`interface ReadWriteStream : `[`Sink`](-sink/index.md)`, `[`Replay`](-replay/index.md) |
| [Replay](-replay/index.md) | Provides a stream of traffic for replaying purposes.`interface Replay` |
| [Responder](-responder/index.md) | Provides HTTP Handlers which respond using pre-stored Requests.`object Responder` |
| [Sink](-sink/index.md) | Consumes HTTP traffic for storage.`interface Sink` |
| [Source](-source/index.md) | Tries to retrieve a stored response for a given request.`interface Source` |

### Functions

| Name | Summary |
|---|---|
| [replayingMatchingContent](replaying-matching-content.md) | `fun `[`Replay`](-replay/index.md)`.replayingMatchingContent(manipulations: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Request`](../org.http4k.core/-request/index.md)` = { it }): `[`HttpHandler`](../org.http4k.core/-http-handler.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Servirtium](-servirtium.md) | Write HTTP traffic to disk in Servirtium markdown format.`fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, options: `[`InteractionOptions`](../org.http4k.servirtium/-interaction-options/index.md)`): `[`Sink`](-sink/index.md)<br>Read HTTP traffic from disk in Servirtium markdown format.`fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, options: `[`InteractionOptions`](../org.http4k.servirtium/-interaction-options/index.md)` = Defaults): `[`Replay`](-replay/index.md) |
