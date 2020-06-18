[http4k](../index.md) / [org.http4k.serverless](./index.md)

## Package org.http4k.serverless

Common code relevant to HTTP serverless implementations.

### Types

| Name | Summary |
|---|---|
| [AppLoader](-app-loader.md) | Http4k app loader - instantiate the application from the environment config`interface AppLoader : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [AppLoaderWithContexts](-app-loader-with-contexts.md) | Http4k app loader - instantiate the application from the environment config and request contexts object`interface AppLoaderWithContexts : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, `[`RequestContexts`](../org.http4k.core/-request-contexts/index.md)`) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) |
| [BootstrapAppLoader](-bootstrap-app-loader/index.md) | `object BootstrapAppLoader : `[`AppLoaderWithContexts`](-app-loader-with-contexts.md) |
| [GoogleCloudFunction](-google-cloud-function/index.md) | `open class GoogleCloudFunction : HttpFunction` |
| [LambdaFunction](-lambda-function/index.md) | This is the main entry point for the lambda. It uses the local environment to instantiate the Http4k handler which can be used for further invocations.`class LambdaFunction` |
| [OpenWhiskFunction](-open-whisk-function/index.md) | `class OpenWhiskFunction : (JsonObject) -> JsonObject` |

### Exceptions

| Name | Summary |
|---|---|
| [BootstrapException](-bootstrap-exception/index.md) | `open class BootstrapException : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [CouldNotFindAppLoaderException](-could-not-find-app-loader-exception/index.md) | `class CouldNotFindAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |
| [InvalidAppLoaderException](-invalid-app-loader-exception/index.md) | `class InvalidAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |

### Properties

| Name | Summary |
|---|---|
| [GCF_REQUEST_KEY](-g-c-f_-r-e-q-u-e-s-t_-k-e-y.md) | `const val GCF_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LAMBDA_CONTEXT_KEY](-l-a-m-b-d-a_-c-o-n-t-e-x-t_-k-e-y.md) | `const val LAMBDA_CONTEXT_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LAMBDA_REQUEST_KEY](-l-a-m-b-d-a_-r-e-q-u-e-s-t_-k-e-y.md) | `const val LAMBDA_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [OW_REQUEST_KEY](-o-w_-r-e-q-u-e-s-t_-k-e-y.md) | `const val OW_REQUEST_KEY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
