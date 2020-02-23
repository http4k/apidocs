[http4k](../../index.md) / [org.http4k.serverless.lambda](../index.md) / [LambdaFunction](./index.md)

# LambdaFunction

`class LambdaFunction`

This is the main entry point for the lambda. It uses the local environment
to instantiate the Http4k handler which can be used for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | This is the main entry point for the lambda. It uses the local environment to instantiate the Http4k handler which can be used for further invocations.`LambdaFunction(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv())` |

### Functions

| Name | Summary |
|---|---|
| [handle](handle.md) | `fun handle(request: APIGatewayProxyRequestEvent, lambdaContext: Context? = null): APIGatewayProxyResponseEvent` |
