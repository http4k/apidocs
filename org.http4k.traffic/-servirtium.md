[http4k](../index.md) / [org.http4k.traffic](index.md) / [Servirtium](./-servirtium.md)

# Servirtium

`fun ReadWriteStream.Companion.Servirtium(baseDir: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)`, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, clean: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`ReadWriteStream`](-read-write-stream/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/traffic/servirtium.kt#L17)

Read and write HTTP traffic to disk in Servirtium markdown format

`fun Sink.Companion.Servirtium(target: `[`Consumer`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Consumer.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>): `[`Sink`](-sink/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/traffic/servirtium.kt#L27)

Write HTTP traffic to disk in Servirtium markdown format

`fun Replay.Companion.Servirtium(output: `[`Supplier`](https://docs.oracle.com/javase/9/docs/api/java/util/function/Supplier.html)`<`[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`>): `[`Replay`](-replay/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/traffic/servirtium.kt#L54)

Read HTTP traffic from disk in Servirtium markdown format

