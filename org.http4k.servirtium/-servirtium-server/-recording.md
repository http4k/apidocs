[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumServer](index.md) / [Recording](./-recording.md)

# Recording

`fun Recording(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`Uri`](../../org.http4k.core/-uri/index.md)`, storageLookup: `[`InteractionStorageLookup`](../-interaction-storage-lookup/index.md)` = Disk(File(".")), requestManipulations: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)` = { it }, responseManipulations: (`[`Response`](../../org.http4k.core/-response/index.md)`) -> `[`Response`](../../org.http4k.core/-response/index.md)` = { it }, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0): `[`ServirtiumServer`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/ServirtiumServer.kt#L46)

MiTM proxy server which sits in between the client and the target and stores traffic in the
named Servirtium Markdown file.

Manipulations can be made to the requests and responses before they are stored.

