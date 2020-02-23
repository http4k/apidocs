[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumServer](./index.md)

# ServirtiumServer

`interface ServirtiumServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, `[`InteractionControl`](../-interaction-control/index.md)

### Companion Object Functions

| Name | Summary |
|---|---|
| [Recording](-recording.md) | MiTM proxy server which sits in between the client and the target and stores traffic in the named Servirtium Markdown file.`fun Recording(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`Uri`](../../org.http4k.core/-uri/index.md)`, storageProvider: `[`StorageProvider`](../-storage-provider.md)`, options: `[`InteractionOptions`](../-interaction-options/index.md)` = Defaults, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, serverFn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)` = ::SunHttp): `[`ServirtiumServer`](./index.md) |
| [Replay](-replay.md) | Replay server which will match and replay recorded traffic read from the named Servirtium Markdown file. Incoming requests can be manipulated to ensure that it matches the expected request.`fun Replay(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, storageProvider: `[`StorageProvider`](../-storage-provider.md)`, options: `[`InteractionOptions`](../-interaction-options/index.md)` = Defaults, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, serverFn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)` = ::SunHttp): `[`ServirtiumServer`](./index.md) |
