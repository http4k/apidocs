[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApiGatewayV2LambdaFunction](./index.md)

# ApiGatewayV2LambdaFunction

`abstract class ApiGatewayV2LambdaFunction : `[`AwsLambdaFunction`](../-aws-lambda-function.md)`<APIGatewayV2HTTPEvent, APIGatewayV2HTTPResponse>`

This is the main entry point for lambda invocations using the V2 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApiGatewayV2LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`ApiGatewayV2LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>This is the main entry point for lambda invocations using the V2 payload format. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`ApiGatewayV2LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `open fun handleRequest(req: APIGatewayV2HTTPEvent, ctx: Context): APIGatewayV2HTTPResponse` |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunctionV2](../../org.http4k.serverless.lambda/-test-function-v2/index.md) | `class TestFunctionV2 : `[`ApiGatewayV2LambdaFunction`](./index.md) |
