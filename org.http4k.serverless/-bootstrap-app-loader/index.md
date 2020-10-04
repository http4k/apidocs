[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [BootstrapAppLoader](./index.md)

# BootstrapAppLoader

`object ~~BootstrapAppLoader~~ : `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)
**Deprecated:** Extend one of the AwsLambdaFunction subclasses instead of this reflection-based approach.

### Properties

| Name | Summary |
|---|---|
| [HTTP4K_BOOTSTRAP_CLASS](-h-t-t-p4-k_-b-o-o-t-s-t-r-a-p_-c-l-a-s-s.md) | `const val HTTP4K_BOOTSTRAP_CLASS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(environment: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, contexts: `[`RequestContexts`](../../org.http4k.core/-request-contexts/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
