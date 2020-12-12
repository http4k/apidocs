[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [InvocationLambdaFunction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`InvocationLambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`
`InvocationLambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)``InvocationLambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)`

This is the main entry point for lambda invocations using the direct invocations.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

