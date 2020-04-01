[http4k](../../index.md) / [org.http4k.routing.experimental](../index.md) / [ResourceLoading](index.md) / [match](./match.md)

# match

`abstract fun match(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`?``open fun match(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`RouterMatch`](../../org.http4k.routing/-router-match/index.md)

Attempt to supply an HttpHandler which can service the passed request.

