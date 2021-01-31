[http4k](../../index.md) / [org.http4k.server](../index.md) / [KtorNetty](./index.md)

# KtorNetty

`data class KtorNetty : `[`ServerConfig`](../-server-config/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `KtorNetty(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)` |

### Properties

| Name | Summary |
|---|---|
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
