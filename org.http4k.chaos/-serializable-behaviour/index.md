[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [SerializableBehaviour](./index.md)

# SerializableBehaviour

`abstract class SerializableBehaviour : `[`ChaosBehaviour`](../-chaos-behaviour.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L22)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SerializableBehaviour(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [type](type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [asFilter](../kotlin.-function1/as-filter.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.asFilter(clock: Clock = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Converts this chaos behaviour to a standard http4k Filter. |
| [then](../kotlin.-function1/then.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.then(nextStage: `[`ChaosStage`](../-chaos-stage.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Chain the next ChaosBehaviour to apply when this stage is finished. |
| [until](../kotlin.-function1/until.md) | `fun `[`ChaosStage`](../-chaos-stage.md)`.until(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosStage`](../-chaos-stage.md)<br>Stop applying the ChaosBehaviour of this stage when the ChaosTrigger fires. |

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
