[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SerializableBehaviour](./index.md)

# SerializableBehaviour

`abstract class SerializableBehaviour : `[`ChaosBehaviour`](../-chaos-behaviour/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L24)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SerializableBehaviour(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [type](type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-chaos-behaviour/invoke.md) | `abstract operator fun invoke(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [BlockThread](../-chaos-behaviours/-block-thread/index.md) | `object BlockThread : `[`SerializableBehaviour`](./index.md)<br>Blocks the current thread. |
| [EatMemory](../-chaos-behaviours/-eat-memory/index.md) | `object EatMemory : `[`SerializableBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [KillProcess](../-chaos-behaviours/-kill-process/index.md) | `object KillProcess : `[`SerializableBehaviour`](./index.md)<br>System exits from the process. |
| [Latency](../-chaos-behaviours/-latency/index.md) | `data class Latency : `[`SerializableBehaviour`](./index.md)<br>Blocks the thread for a random amount of time within the allocated range. |
| [NoBody](../-chaos-behaviours/-no-body/index.md) | `object NoBody : `[`SerializableBehaviour`](./index.md)<br>Strips the body from a response. |
| [ReturnStatus](../-chaos-behaviours/-return-status/index.md) | `data class ReturnStatus : `[`SerializableBehaviour`](./index.md)<br>Returns an empty response with the appropriate status. |
| [StackOverflow](../-chaos-behaviours/-stack-overflow/index.md) | `object StackOverflow : `[`SerializableBehaviour`](./index.md)<br>Allocates memory in a busy loop until an OOM occurs. |
| [ThrowException](../-chaos-behaviours/-throw-exception/index.md) | `data class ThrowException : `[`SerializableBehaviour`](./index.md)<br>Throws the appropriate exception. |
