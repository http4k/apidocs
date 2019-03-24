[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [Http4kK8sServer](./index.md)

# Http4kK8sServer

`class Http4kK8sServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/Http4kK8sServer.kt#L17)

A K8S server consists of a main application and a health application, running on 2 different ports.
This class provides unified start/stop control.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Http4kK8sServer(main: `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, health: `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`)`<br>A K8S server consists of a main application and a health application, running on 2 different ports. This class provides unified start/stop control. |

### Functions

| Name | Summary |
|---|---|
| [healthPort](health-port.md) | `fun healthPort(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [port](port.md) | `fun port(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [start](start.md) | `fun start(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [stop](stop.md) | `fun stop(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [block](../../org.http4k.server/-http4k-server/block.md) | `open fun block(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [close](../../org.http4k.server/-http4k-server/close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
