[http4k](../../index.md) / [org.http4k.serverless](../index.md) / [OpenWhiskFunction](./index.md)

# OpenWhiskFunction

`class OpenWhiskFunction : (JsonObject) -> JsonObject`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OpenWhiskFunction(input: `[`AppLoader`](../-app-loader.md)`, env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv(), detectBinaryBody: `[`DetectBinaryBody`](../-detect-binary-body/index.md)` = NonBinary)`<br>`OpenWhiskFunction(appLoader: `[`AppLoaderWithContexts`](../-app-loader-with-contexts.md)`, env: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = System.getenv(), detectBinaryBody: `[`DetectBinaryBody`](../-detect-binary-body/index.md)` = NonBinary)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(request: JsonObject): JsonObject` |
