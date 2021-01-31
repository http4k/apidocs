[http4k](../../index.md) / [org.http4k.server](../index.md) / [Apache4Server](./index.md)

# Apache4Server

`data class Apache4Server : `[`ServerConfig`](../-server-config/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Apache4Server(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000)`<br>`Apache4Server(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 8000, address: `[`InetAddress`](https://docs.oracle.com/javase/9/docs/api/java/net/InetAddress.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [address](address.md) | `val address: `[`InetAddress`](https://docs.oracle.com/javase/9/docs/api/java/net/InetAddress.html)`?` |
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [toServer](to-server.md) | `fun toServer(http: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`Http4kServer`](../-http4k-server/index.md) |
