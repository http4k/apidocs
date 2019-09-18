[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [BootstrapException](./index.md)

# BootstrapException

`open class BootstrapException : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-serverless-lambda/src/main/kotlin/org/http4k/serverless/BootstrapAppLoader.kt#L24)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BootstrapException(m: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, cause: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`? = null)` |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [CouldNotFindAppLoaderException](../-could-not-find-app-loader-exception/index.md) | `class CouldNotFindAppLoaderException : `[`BootstrapException`](./index.md) |
| [InvalidAppLoaderException](../-invalid-app-loader-exception/index.md) | `class InvalidAppLoaderException : `[`BootstrapException`](./index.md) |
