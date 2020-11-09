[http4k](../index.md) / [org.http4k.routing](index.md) / [hostDemux](./host-demux.md)

# hostDemux

`fun hostDemux(head: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`RoutingHttpHandler`](-routing-http-handler/index.md)`>, vararg tail: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`RoutingHttpHandler`](-routing-http-handler/index.md)`>): `[`RoutingHttpHandler`](-routing-http-handler/index.md)

Matches the Host header to a matching Handler.

