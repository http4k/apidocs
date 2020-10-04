[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApiGatewayV1LambdaFunction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`ApiGatewayV1LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`
`ApiGatewayV1LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)``ApiGatewayV1LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)`

This is the main entry point for lambda invocations using the V1 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

