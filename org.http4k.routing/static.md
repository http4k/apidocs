[http4k](../index.md) / [org.http4k.routing](index.md) / [static](./static.md)

# static

`fun static(resourceLoader: `[`ResourceLoader`](-resource-loader/index.md)` = ResourceLoader.Classpath(), vararg extraFileExtensionToContentTypes: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`ContentType`](../org.http4k.core/-content-type/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md)

Serve static content using the passed ResourceLoader. Note that for security, by default ONLY mime-types registered in
mime.types (resource file) will be served. All other types are registered as application/octet-stream and are not served.

