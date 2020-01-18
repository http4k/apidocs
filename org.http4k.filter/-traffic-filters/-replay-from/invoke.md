[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [TrafficFilters](../index.md) / [ReplayFrom](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(replay: `[`Replay`](../../../org.http4k.traffic/-replay/index.md)`, matchFn: (`[`Request`](../../../org.http4k.core/-request/index.md)`, `[`Request`](../../../org.http4k.core/-request/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { received, stored -> received.toString() != stored.toString() }): `[`Filter`](../../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/filter/TrafficFilters.kt#L31)