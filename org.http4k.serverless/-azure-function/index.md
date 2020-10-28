[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [AzureFunction](./index.md)

# AzureFunction

`abstract class AzureFunction`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AzureFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`AzureFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>`AzureFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: HttpRequestMessage<`[`Optional`](https://docs.oracle.com/javase/9/docs/api/java/util/Optional.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>, ctx: ExecutionContext): <ERROR CLASS>` |
| [handleRequest](handle-request.md) | `abstract fun handleRequest(req: HttpRequestMessage<`[`Optional`](https://docs.oracle.com/javase/9/docs/api/java/util/Optional.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>, ctx: ExecutionContext): HttpResponseMessage` |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunction](../../org.http4k.serverless.azure/-test-function/index.md) | `class TestFunction : `[`AzureFunction`](./index.md) |
