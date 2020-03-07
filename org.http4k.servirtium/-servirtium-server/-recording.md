[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [ServirtiumServer](index.md) / [Recording](./-recording.md)

# Recording

`@JvmStatic fun Recording(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`Uri`](../../org.http4k.core/-uri/index.md)`, storageProvider: `[`StorageProvider`](../-storage-provider.md)`, options: `[`InteractionOptions`](../-interaction-options/index.md)` = Defaults, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, serverFn: (`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`ServerConfig`](../../org.http4k.server/-server-config/index.md)` = ::SunHttp, proxyClient: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)` = ApacheClient()): `[`ServirtiumServer`](index.md)

MiTM proxy server which sits in between the client and the target and stores traffic in the
named Servirtium Markdown file.

Manipulations can be made to the requests and responses before they are stored.

