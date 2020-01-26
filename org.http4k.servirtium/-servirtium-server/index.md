[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumServer](./index.md)

# ServirtiumServer

`interface ServirtiumServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, `[`RecordingControl`](../-recording-control/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/ServirtiumServer.kt#L21)

### Inherited Functions

| Name | Summary |
|---|---|
| [addNote](../-recording-control/add-note.md) | `abstract fun addNote(note: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [block](../../org.http4k.server/-http4k-server/block.md) | `open fun block(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [close](../../org.http4k.server/-http4k-server/close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [port](../../org.http4k.server/-http4k-server/port.md) | `abstract fun port(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [start](../../org.http4k.server/-http4k-server/start.md) | `abstract fun start(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [stop](../../org.http4k.server/-http4k-server/stop.md) | `abstract fun stop(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Recording](-recording.md) | `fun Recording(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`Uri`](../../org.http4k.core/-uri/index.md)`, root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."), port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = { it }): `[`ServirtiumServer`](./index.md)<br>MiTM proxy server which sits inbetween the client and the target and stores traffic in the named Servirtium Markdown file. |
| [Replay](-replay.md) | `fun Replay(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."), port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }): `[`ServirtiumServer`](./index.md)<br>Replay server which will match and replay recorded traffic read from the named Servirtium Markdown file. Incoming requests can be manipulated to ensure that it matches the expected request. |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
