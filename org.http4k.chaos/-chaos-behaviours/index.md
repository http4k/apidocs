[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviours](./index.md)

# ChaosBehaviours

`object ChaosBehaviours` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L24)

### Types

| Name | Summary |
|---|---|
| [BlockThread](-block-thread/index.md) | `object BlockThread : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Blocks the current thread. |
| [EatMemory](-eat-memory/index.md) | `object EatMemory : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](-kill-process/index.md) | `object KillProcess : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>System exits from the process. |
| [Latency](-latency/index.md) | `data class Latency : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Blocks the thread for a random amount of time within the allocated range. |
| [NoBody](-no-body/index.md) | `object NoBody : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Strips the body from a response. |
| [ReturnStatus](-return-status/index.md) | `data class ReturnStatus : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Returns an empty response with the appropriate status. |
| [StackOverflow](-stack-overflow/index.md) | `object StackOverflow : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](-throw-exception/index.md) | `data class ThrowException : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Throws the appropriate exception. |
| [Variable](-variable/index.md) | `data class Variable : `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |

### Properties

| Name | Summary |
|---|---|
| [None](-none.md) | `val None: `[`ChaosBehaviour`](../-chaos-behaviour/index.md)<br>Does absolutely nothing. |
