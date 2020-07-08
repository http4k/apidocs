[http4k](../../index.md) / [org.http4k.client](../index.md) / [JavaHttpClient](./index.md)

# JavaHttpClient

`class JavaHttpClient : `[`HttpHandler`](../../org.http4k.core/-http-handler.md)

Basic JDK-based Client.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Basic JDK-based Client.`JavaHttpClient(httpClient: HttpClient = defaultJavaHttpClient(), requestBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory, responseBodyMode: `[`BodyMode`](../../org.http4k.core/-body-mode/index.md)` = Memory)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
