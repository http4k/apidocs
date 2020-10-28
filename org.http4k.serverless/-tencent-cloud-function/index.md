[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [TencentCloudFunction](./index.md)

# TencentCloudFunction

`abstract class TencentCloudFunction`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TencentCloudFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`TencentCloudFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>`TencentCloudFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `fun handleRequest(request: APIGatewayProxyRequestEvent, context: Context?): <ERROR CLASS>` |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunction](../../tencent/-test-function/index.md) | `class TestFunction : `[`TencentCloudFunction`](./index.md) |
