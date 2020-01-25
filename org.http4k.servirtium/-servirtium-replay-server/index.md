[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumReplayServer](./index.md)

# ServirtiumReplayServer

`object ServirtiumReplayServer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/ServirtiumReplayServer.kt#L16)

MiTM replay server which will match and replay recorded traffic read from the named Servirtium Markdown file.
Incoming requests can be manipulated to ensure that it matches the expected request.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."), port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, manipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
