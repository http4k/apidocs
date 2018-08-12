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
| [SerializableBehaviour](../-serializable-behaviour/index.md) | `abstract class SerializableBehaviour : `[`ChaosBehaviour`](./index.md) |
| [Variable](../-chaos-behaviours/-variable/index.md) | `data class Variable : `[`ChaosBehaviour`](./index.md)<br>Provide a means of modifying a ChaosBehaviour at runtime. |
