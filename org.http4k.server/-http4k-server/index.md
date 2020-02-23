[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kServer](./index.md)

# Http4kServer

`interface Http4kServer : `[`AutoCloseable`](https://docs.oracle.com/javase/9/docs/api/java/lang/AutoCloseable.html)

### Functions

| Name | Summary |
|---|---|
| [block](block.md) | `open fun block(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [close](close.md) | `open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [port](port.md) | `abstract fun port(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [start](start.md) | `abstract fun start(): `[`Http4kServer`](./index.md) |
| [stop](stop.md) | `abstract fun stop(): `[`Http4kServer`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Http4kK8sServer](../../org.http4k.cloudnative/-http4k-k8s-server/index.md) | A K8S server consists of a main application and a health application, running on 2 different ports. This class provides unified start/stop control.`class Http4kK8sServer : `[`Http4kServer`](./index.md) |
| [ServirtiumServer](../../org.http4k.servirtium/-servirtium-server/index.md) | `interface ServirtiumServer : `[`Http4kServer`](./index.md)`, `[`InteractionControl`](../../org.http4k.servirtium/-interaction-control/index.md) |
