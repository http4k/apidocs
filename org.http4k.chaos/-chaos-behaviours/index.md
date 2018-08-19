[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviours](./index.md)

# ChaosBehaviours

`object ChaosBehaviours` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L22)

### Types

| Name | Summary |
|---|---|
| [Latency](-latency/index.md) | `object Latency`<br>Blocks the thread for a random amount of time within the allocated range. |
| [Variable](-variable/index.md) | `class Variable : `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |

### Properties

| Name | Summary |
|---|---|
| [None](-none.md) | `val None: `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Does absolutely nothing. |

### Functions

| Name | Summary |
|---|---|
| [BlockThread](-block-thread.md) | `fun BlockThread(): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Blocks the current thread. |
| [EatMemory](-eat-memory.md) | `fun EatMemory(): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](-kill-process.md) | `fun KillProcess(): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>System exits from the process. |
| [NoBody](-no-body.md) | `fun NoBody(): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Strips the body from a response. |
| [ReturnStatus](-return-status.md) | `fun ReturnStatus(status: `[`Status`](../../org.http4k.core/-status/index.md)` = INTERNAL_SERVER_ERROR): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Returns an empty response with the appropriate status. |
| [StackOverflow](-stack-overflow.md) | `fun StackOverflow(): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](-throw-exception.md) | `fun ThrowException(e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)` = Exception("Chaos behaviour injected!")): `[`ChaosBehaviour`](../-chaos-behaviour.md)<br>Throws the appropriate exception. |
