[http4k](../../index.md) / [org.http4k.client](../index.md) / [ApacheAsyncClient](./index.md)

# ApacheAsyncClient

`object ApacheAsyncClient` [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-apache-async/src/main/kotlin/org/http4k/client/ApacheAsyncClient.kt#L28)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(client: CloseableHttpAsyncClient = defaultApacheAsyncHttpClient(), responseBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory, requestBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory): `[`AsyncHttpClient`](../-async-http-client/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
