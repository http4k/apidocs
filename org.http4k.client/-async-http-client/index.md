[http4k](../../index.md) / [org.http4k.client](../index.md) / [AsyncHttpClient](./index.md)

# AsyncHttpClient

`interface AsyncHttpClient : `[`Closeable`](http://docs.oracle.com/javase/6/docs/api/java/io/Closeable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/client/ext.kt#L8)

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [invoke](invoke.md) | `abstract operator fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`, fn: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [DualSyncAsyncHttpHandler](../-dual-sync-async-http-handler.md) | `interface DualSyncAsyncHttpHandler : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](./index.md) |
