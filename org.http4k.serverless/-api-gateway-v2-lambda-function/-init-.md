[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [ApiGatewayV2LambdaFunction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`ApiGatewayV2LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`
`ApiGatewayV2LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)``ApiGatewayV2LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)`

This is the main entry point for lambda invocations using the V2 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

