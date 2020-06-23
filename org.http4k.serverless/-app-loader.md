[http4k](../index.md) / [org.http4k.serverless](index.md) / [AppLoader](./-app-loader.md)

# AppLoader

`interface AppLoader : (`[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>) -> `[`HttpHandler`](../org.http4k.core/-http-handler.md)

Http4k app loader - instantiate the application from the environment config

### Inheritors

| Name | Summary |
|---|---|
| [TestServerlessFunction](../org.http4k.serverless.lambda/-test-serverless-function/index.md) | `object TestServerlessFunction : `[`AppLoader`](./-app-loader.md) |
| [TestServerlessFunction](../org.http4k.serverless.openwhisk/-test-serverless-function/index.md) | `object TestServerlessFunction : `[`AppLoader`](./-app-loader.md) |
