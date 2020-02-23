[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutingHttpHandler](index.md) / [withBasePath](./with-base-path.md)

# withBasePath

`abstract fun withBasePath(new: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`RoutingHttpHandler`](index.md)

Returns a RoutingHttpHandler which prepends the passed base path to the logic determining the match()
To follow the trend of immutability, this will generally be a new instance.

