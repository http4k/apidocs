[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [Http4kK8sServer](./index.md)

# Http4kK8sServer

`class Http4kK8sServer : `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)

A K8S server consists of a main application and a health application, running on 2 different ports.
This class provides unified start/stop control.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A K8S server consists of a main application and a health application, running on 2 different ports. This class provides unified start/stop control.`Http4kK8sServer(main: `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`, health: `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [healthPort](health-port.md) | `fun healthPort(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [port](port.md) | `fun port(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [start](start.md) | `fun start(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
| [stop](stop.md) | `fun stop(): `[`Http4kServer`](../../org.http4k.server/-http4k-server/index.md) |
