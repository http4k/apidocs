[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [LambdaFunction](./index.md)

# LambdaFunction

`open class ~~LambdaFunction~~ : `[`ApiGatewayV1LambdaFunction`](../-api-gateway-v1-lambda-function/index.md)
**Deprecated:** Extend one of the specific AwsLambdaFunction subclasses instead.

This is the main entry point for lambda invocations using the V1 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>`LambdaFunction(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv())`<br>This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |
