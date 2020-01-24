[http4k](../index.md) / [org.http4k.traffic](index.md) / [Servirtium](./-servirtium.md)

# Servirtium

`fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, requestManipulations: (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Request`](../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../org.http4k.core/-response/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { it }): `[`Sink`](-sink/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/traffic/servirtium.kt#L16)

Write HTTP traffic to disk in Servirtium markdown format

`fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>, manipulations: (`[`Response`](../org.http4k.core/-response/index.md)`) -> `[`Response`](../org.http4k.core/-response/index.md)` = { it }): `[`Replay`](-replay/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/traffic/servirtium.kt#L49)

Read HTTP traffic from disk in Servirtium markdown format

