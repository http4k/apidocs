[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApiGatewayV1LambdaFunction](./index.md)

# ApiGatewayV1LambdaFunction

`abstract class ApiGatewayV1LambdaFunction : `[`AwsLambdaFunction`](../-aws-lambda-function.md)`<APIGatewayProxyRequestEvent, APIGatewayProxyResponseEvent>`

This is the main entry point for lambda invocations using the V1 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApiGatewayV1LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`ApiGatewayV1LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`ApiGatewayV1LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `open fun handleRequest(req: APIGatewayProxyRequestEvent, ctx: Context): APIGatewayProxyResponseEvent` |

### Inheritors

| Name | Summary |
|---|---|
| [LambdaFunction](../-lambda-function/index.md) | This is the main entry point for lambda invocations using the V1 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`open class ~~LambdaFunction~~ : `[`ApiGatewayV1LambdaFunction`](./index.md) |
| [TestFunctionV1](../../org.http4k.serverless.lambda/-test-function-v1/index.md) | `class TestFunctionV1 : `[`ApiGatewayV1LambdaFunction`](./index.md) |
