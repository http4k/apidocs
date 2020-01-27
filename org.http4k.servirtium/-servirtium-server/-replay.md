[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumServer](index.md) / [Replay](./-replay.md)

# Replay

`fun Replay(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, storageLookup: `[`InteractionStorageLookup`](../-interaction-storage-lookup/index.md)` = Disk(File(".")), port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }): `[`ServirtiumServer`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/ServirtiumServer.kt#L28)

Replay server which will match and replay recorded traffic read from the named Servirtium Markdown file.
Incoming requests can be manipulated to ensure that it matches the expected request.

