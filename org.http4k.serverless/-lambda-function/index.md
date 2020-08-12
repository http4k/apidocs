[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [LambdaFunction](./index.md)

# LambdaFunction

`open class LambdaFunction`

This is the main entry point for the lambda. It uses the local environment
to instantiate the Http4k handler which can be used for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>`LambdaFunction(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv())`<br>This is the main entry point for the lambda. It uses the local environment to instantiate the Http4k handler which can be used for further invocations.`LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: APIGatewayProxyRequestEvent, lambdaContext: Context? = null): APIGatewayProxyResponseEvent` |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunction](../../org.http4k.serverless.lambda/-test-function/index.md) | `class TestFunction : `[`LambdaFunction`](./index.md) |
