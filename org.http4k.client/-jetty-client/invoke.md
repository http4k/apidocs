[http4k](../../index.md) / [org.http4k.client](../index.md) / [JettyClient](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(client: HttpClient = defaultHttpClient(), bodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = BodyMode.Memory, requestModifier: (Request) -> Request = { it }): `[`DualSyncAsyncHttpHandler`](../-dual-sync-async-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-client-jetty/src/main/kotlin/org/http4k/client/JettyClient.kt#L23)