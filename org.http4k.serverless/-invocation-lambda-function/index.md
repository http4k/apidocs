[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [InvocationLambdaFunction](./index.md)

# InvocationLambdaFunction

`abstract class InvocationLambdaFunction : `[`AwsLambdaFunction`](../-aws-lambda-function/index.md)`<`[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`>, RequestStreamHandler`

This is the main entry point for lambda invocations using the direct invocations.
It uses the local environment to instantiate the HttpHandler which can be used
for further invocations.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InvocationLambdaFunction(input: `[`AppLoader`](../-app-loader.md)`)`<br>`InvocationLambdaFunction(input: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`)`<br>This is the main entry point for lambda invocations using the direct invocations. It uses the local environment to instantiate the HttpHandler which can be used for further invocations.`InvocationLambdaFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [handleRequest](handle-request.md) | `open fun handleRequest(input: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, output: `[`OutputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/OutputStream.html)`, context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [TestFunctionInvocation](../../org.http4k.serverless.lambda/-test-function-invocation/index.md) | `class TestFunctionInvocation : `[`InvocationLambdaFunction`](./index.md) |
