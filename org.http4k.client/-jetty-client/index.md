[http4k](../../index.md) / [org.http4k.client](../index.md) / [JettyClient](./index.md)

# JettyClient

`object JettyClient` [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-jetty/src/main/kotlin/org/http4k/client/JettyClient.kt#L27)

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(client: HttpClient = defaultHttpClient(), bodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = BodyMode.Memory, requestModifier: (Request) -> Request = { it }): `[`DualSyncAsyncHttpHandler`](../-dual-sync-async-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
