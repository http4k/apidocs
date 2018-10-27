[http4k](../../index.md) / [org.http4k.server](../index.md) / [Http4kServer](./index.md)

# Http4kServer

`interface Http4kServer : `[`AutoCloseable`](http://docs.oracle.com/javase/6/docs/api/java/lang/AutoCloseable.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/server/http4kServer.kt#L9)

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
| [Http4kK8sServer](../../org.http4k.k8s/-http4k-k8s-server/index.md) | `class Http4kK8sServer : `[`Http4kServer`](./index.md)<br>A K8S server consists of a main application and a health application, running on 2 different ports. |
