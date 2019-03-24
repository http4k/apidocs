[http4k](../../index.md) / [org.http4k.client](../index.md) / [ApacheClient](./index.md)

# ApacheClient

`object ApacheClient` [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-apache/src/main/kotlin/org/http4k/client/ApacheClient.kt#L41)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(client: CloseableHttpClient = defaultApacheHttpClient(), responseBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory, requestBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
