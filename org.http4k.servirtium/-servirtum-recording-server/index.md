[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtumRecordingServer](./index.md)

# ServirtumRecordingServer

`object ServirtumRecordingServer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/ServirtumRecordingServer.kt#L23)

MiTM proxy server which sits inbetween the client and the target and stores traffic in the
named Servirtium Markdown file.

Manipulations can be made to the requests and responses before they are stored.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`Uri`](../../org.http4k.core/-uri/index.md)`, root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."), port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = { it }): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
