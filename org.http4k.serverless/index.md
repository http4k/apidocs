[http4k](../index.md) / [org.http4k.serverless](./index.md)

## Package org.http4k.serverless

Common code relevant to HTTP serverless implementations.

### Types

| Name | Summary |
|---|---|
| [AppLoader](-app-loader.md) | `interface AppLoader : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md)<br>Http4k app loader - instantiate the application from the environment config |
| [AppLoaderWithContexts](-app-loader-with-contexts.md) | `interface AppLoaderWithContexts : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, `[`RequestContexts`](../org.http4k.core/-request-contexts/index.md)`) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md)<br>Http4k app loader - instantiate the application from the environment config and request contexts object |
| [BootstrapAppLoader](-bootstrap-app-loader/index.md) | `object BootstrapAppLoader : `[`AppLoaderWithContexts`](-app-loader-with-contexts.md) |

### Exceptions

| Name | Summary |
|---|---|
| [BootstrapException](-bootstrap-exception/index.md) | `open class BootstrapException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
| [CouldNotFindAppLoaderException](-could-not-find-app-loader-exception/index.md) | `class CouldNotFindAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |
| [InvalidAppLoaderException](-invalid-app-loader-exception/index.md) | `class InvalidAppLoaderException : `[`BootstrapException`](-bootstrap-exception/index.md) |
