[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviour](./index.md)

# ChaosBehaviour

`interface ChaosBehaviour` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviour.kt#L20)

Encapsulates the type of bad behaviour to apply to the response.

### Types

| Name | Summary |
|---|---|
| [Latency](-latency/index.md) | `object Latency`<br>Blocks the thread for a random amount of time within the allocated range. |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun invoke(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [BlockThread](-block-thread.md) | `fun BlockThread(): `[`ChaosBehaviour`](./index.md)<br>Blocks the current thread. |
| [EatMemory](-eat-memory.md) | `fun EatMemory(): `[`ChaosBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](-kill-process.md) | `fun KillProcess(): `[`ChaosBehaviour`](./index.md)<br>System exits from the process. |
| [NoBody](-no-body.md) | `fun NoBody(): `[`ChaosBehaviour`](./index.md)<br>Strips the body from a response. |
| [ReturnStatus](-return-status.md) | `fun ReturnStatus(status: `[`Status`](../../org.http4k.core/-status/index.md)` = INTERNAL_SERVER_ERROR): `[`ChaosBehaviour`](./index.md)<br>Returns an empty response with the appropriate status. |
| [StackOverflow](-stack-overflow.md) | `fun StackOverflow(): `[`ChaosBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](-throw-exception.md) | `fun ThrowException(e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)` = Exception("Chaos behaviour injected!")): `[`ChaosBehaviour`](./index.md)<br>Throws the appropriate exception. |
