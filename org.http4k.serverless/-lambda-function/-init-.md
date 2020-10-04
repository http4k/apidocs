[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [LambdaFunction](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`LambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`
`LambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`
`LambdaFunction(env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv())``LambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)`

This is the main entry point for lambda invocations using the V1 payload format.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

