[http4k](../index.md) / [org.http4k.serverless](index.md) / [AppLoader](./-app-loader.md)

# AppLoader

`interface AppLoader : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-serverless-lambda/src/main/kotlin/org/http4k/serverless/AppLoader.kt#L8)

Http4k app loader - instantiate the application from the environment config

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
