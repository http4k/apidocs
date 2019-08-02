[http4k](../index.md) / [org.http4k.routing](index.md) / [singlePageApp](./single-page-app.md)

# singlePageApp

`fun singlePageApp(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = ResourceLoader.Classpath("/public"), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L63)

For SPAs we serve static content as usual, or fall back to the index page. The resource loader is configured to look at
/public package (on the Classpath).

