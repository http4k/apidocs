[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [BootstrapAppLoader](./index.md)

# BootstrapAppLoader

`object BootstrapAppLoader : `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-serverless-lambda/src/main/kotlin/org/http4k/serverless/BootstrapAppLoader.kt#L14)

### Properties

| Name | Summary |
|---|---|
| [HTTP4K_BOOTSTRAP_CLASS](-h-t-t-p4-k_-b-o-o-t-s-t-r-a-p_-c-l-a-s-s.md) | `const val HTTP4K_BOOTSTRAP_CLASS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(environment: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
