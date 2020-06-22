[http4k](../index.md) / [org.http4k.client](./index.md)

## Package org.http4k.client

Common code relevant to HTTP client implementations.

### Types

| Name | Summary |
|---|---|
| [Apache4AsyncClient](-apache4-async-client/index.md) | `object Apache4AsyncClient` |
| [Apache4Client](-apache4-client/index.md) | `object Apache4Client` |
| [ApacheAsyncClient](-apache-async-client/index.md) | `object ApacheAsyncClient` |
| [ApacheClient](-apache-client/index.md) | `object ApacheClient` |
| [AsyncHttpClient](-async-http-client/index.md) | `interface AsyncHttpClient : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html) |
| [DualSyncAsyncHttpHandler](-dual-sync-async-http-handler.md) | `interface DualSyncAsyncHttpHandler : `[`HttpHandler`](../org.http4k.core/-http-handler.md)`, `[`AsyncHttpClient`](-async-http-client/index.md) |
| [JavaHttpClient](-java-http-client/index.md) | `object JavaHttpClient` |
| [JettyClient](-jetty-client/index.md) | `object JettyClient` |
| [OkHttp](-ok-http/index.md) | `object OkHttp` |
| [PreCannedApache4HttpClients](-pre-canned-apache4-http-clients/index.md) | `object PreCannedApache4HttpClients` |
| [PreCannedApacheHttpClients](-pre-canned-apache-http-clients/index.md) | `object PreCannedApacheHttpClients` |
| [WebsocketClient](-websocket-client/index.md) | `object WebsocketClient` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [toClientStatus](to-client-status.md) | `fun `[`Status`](../org.http4k.core/-status/index.md)`.toClientStatus(e: `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html)`): `[`Status`](../org.http4k.core/-status/index.md) |
