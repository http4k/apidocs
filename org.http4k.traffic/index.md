[http4k](../index.md) / [org.http4k.traffic](./index.md)

## Package org.http4k.traffic

### Types

| Name | Summary |
|---|---|
| [ByteStorage](-byte-storage/index.md) | `interface ByteStorage : `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>`<br>Generic wrapper interface to provide data storage |
| [ReadWriteCache](-read-write-cache/index.md) | `interface ReadWriteCache : `[`Sink`](-sink/index.md)`, `[`Source`](-source/index.md)<br>Combined Read/Write storage models, optimised for retrieval. |
| [ReadWriteStream](-read-write-stream/index.md) | `interface ReadWriteStream : `[`Sink`](-sink/index.md)`, `[`Replay`](-replay/index.md)<br>Combined Read/Write storage models, optimised for replay. |
| [Replay](-replay/index.md) | `interface Replay`<br>Provides a stream of traffic for replaying purposes. |
| [Responder](-responder/index.md) | `object Responder`<br>Provides HTTP Handlers which respond using pre-stored Requests. |
| [Sink](-sink/index.md) | `interface Sink`<br>Consumes HTTP traffic for storage. |
| [Source](-source/index.md) | `interface Source`<br>Tries to retrieve a stored response for a given request. |

### Functions

| Name | Summary |
|---|---|
| [replayingMatchingContent](replaying-matching-content.md) | `fun `[`Replay`](-replay/index.md)`.replayingMatchingContent(manipulations: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Request`](../org.http4k.core/-request/index.md)` = { it }): `[`HttpHandler`](../org.http4k.core/-http-handler.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Servirtium](-servirtium.md) | `fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, requestManipulations: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Request`](../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../org.http4k.core/-response/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { it }): `[`Sink`](-sink/index.md)<br>Write HTTP traffic to disk in Servirtium markdown format`fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>): `[`Replay`](-replay/index.md)<br>Read HTTP traffic from disk in Servirtium markdown format |
