[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviour](./index.md)

# ChaosBehaviour

`interface ChaosBehaviour` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L20)

Encapsulates the type of bad behaviour to apply to the response.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [BlockThread](../-chaos-behaviours/-block-thread/index.md) | `object BlockThread : `[`ChaosBehaviour`](./index.md)<br>Blocks the current thread. |
| [EatMemory](../-chaos-behaviours/-eat-memory/index.md) | `object EatMemory : `[`ChaosBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](../-chaos-behaviours/-kill-process/index.md) | `object KillProcess : `[`ChaosBehaviour`](./index.md)<br>System exits from the process. |
| [Latency](../-chaos-behaviours/-latency/index.md) | `data class Latency : `[`ChaosBehaviour`](./index.md)<br>Blocks the thread for a random amount of time within the allocated range. |
| [NoBody](../-chaos-behaviours/-no-body/index.md) | `object NoBody : `[`ChaosBehaviour`](./index.md)<br>Strips the body from a response. |
| [ReturnStatus](../-chaos-behaviours/-return-status/index.md) | `data class ReturnStatus : `[`ChaosBehaviour`](./index.md)<br>Returns an empty response with the appropriate status. |
| [StackOverflow](../-chaos-behaviours/-stack-overflow/index.md) | `object StackOverflow : `[`ChaosBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](../-chaos-behaviours/-throw-exception/index.md) | `data class ThrowException : `[`ChaosBehaviour`](./index.md)<br>Throws the appropriate exception. |
| [Variable](../-chaos-behaviours/-variable/index.md) | `data class Variable : `[`ChaosBehaviour`](./index.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |
