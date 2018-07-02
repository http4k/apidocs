[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosPolicy](../index.md) / [Always](./index.md)

# Always

`object Always : `[`ChaosPolicy`](../index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicy.kt#L49)

Applies to every transaction.

### Functions

| Name | Summary |
|---|---|
| [appliesTo](applies-to.md) | `fun appliesTo(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../inject.md) | `open fun inject(behaviour: `[`ChaosBehaviour`](../../-chaos-behaviour/index.md)`): `[`ChaosStage`](../../-chaos-stage/index.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |
