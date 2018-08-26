[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoading](index.md) / [match](./match.md)

# match

`abstract fun match(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/routing/experimental/ResourceLoaders.kt#L51)`open fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?` [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/routing/experimental/ResourceLoaders.kt#L53)

Overrides [Router.match](../../org.http4k.routing/-router/match.md)

Attempt to supply an HttpHandler which can service the passed request.

