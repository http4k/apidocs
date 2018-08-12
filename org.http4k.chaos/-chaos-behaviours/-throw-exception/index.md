[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [ThrowException](./index.md)

# ThrowException

`data class ThrowException : `[`ChaosBehaviour`](../../-chaos-behaviour.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L54)

Throws the appropriate exception.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ThrowException(e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)` = Exception("Chaos behaviour injected!"))`<br>Throws the appropriate exception. |

### Properties

| Name | Summary |
|---|---|
| [e](e.md) | `val e: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
