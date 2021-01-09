[http4k](../index.md) / [org.http4k.routing](index.md) / [reverseProxy](./reverse-proxy.md)

# reverseProxy

`fun reverseProxy(vararg hostToHandler: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`HttpHandler`](../org.http4k.core/-http-handler.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md)

Simple Reverse Proxy which will split and direct traffic to the appropriate
HttpHandler based on the content of the Host header

