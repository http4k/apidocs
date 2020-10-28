[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [AlibabaCloudFunction](./index.md)

# AlibabaCloudFunction

`abstract class AlibabaCloudFunction : HttpRequestHandler`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AlibabaCloudFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`AlibabaCloudFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>`AlibabaCloudFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `open fun handleRequest(request: HttpServletRequest, response: HttpServletResponse, context: Context?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunction](../../org.http4k.serverless.alibaba/-test-function/index.md) | `class TestFunction : `[`AlibabaCloudFunction`](./index.md) |
