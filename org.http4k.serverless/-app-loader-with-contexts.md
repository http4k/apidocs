[http4k](../index.md) / [org.http4k.serverless](index.md) / [AppLoaderWithContexts](./-app-loader-with-contexts.md)

# AppLoaderWithContexts

`interface AppLoaderWithContexts : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, `[`RequestContexts`](../org.http4k.core/-request-contexts/index.md)`) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-serverless-lambda/src/main/kotlin/org/http4k/serverless/AppLoaderWithContexts.kt#L9)

Http4k app loader - instantiate the application from the environment config and request contexts object

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [BootstrapAppLoader](-bootstrap-app-loader/index.md) | `object BootstrapAppLoader : `[`AppLoaderWithContexts`](./-app-loader-with-contexts.md) |
