[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [ReturnStatus](./index.md)

# ReturnStatus

`data class ReturnStatus : `[`SerializableBehaviour`](../../-serializable-behaviour/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L67)

Returns an empty response with the appropriate status.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ReturnStatus(status: `[`Status`](../../../org.http4k.core/-status/index.md)` = INTERNAL_SERVER_ERROR)`<br>Returns an empty response with the appropriate status. |

### Inherited Properties

| Name | Summary |
|---|---|
| [type](../../-serializable-behaviour/type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../../org.http4k.core/-response/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
