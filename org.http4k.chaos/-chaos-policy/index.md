[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicy](./index.md)

# ChaosPolicy

`interface ChaosPolicy` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L11)

Determines whether or not to apply a particular type of ChaosBehaviour to a request/response.

### Functions

| Name | Summary |
|---|---|
| [appliesTo](applies-to.md) | `open fun appliesTo(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [inject](inject.md) | `open fun inject(behaviour: `[`ChaosBehaviour`](../-chaos-behaviour/index.md)`): `[`ChaosStage`](../-chaos-stage/index.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |

### Inheritors

| Name | Summary |
|---|---|
| [Always](../-chaos-policies/-always/index.md) | `object Always : `[`ChaosPolicy`](./index.md)<br>Applies to every transaction. |
| [Once](../-chaos-policies/-once/index.md) | `data class Once : `[`ChaosPolicy`](./index.md)<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [Only](../-chaos-policies/-only/index.md) | `data class Only : `[`ChaosPolicy`](./index.md)<br>Application predicated on the ChaosTrigger |
| [PercentageBased](../-chaos-policies/-percentage-based/index.md) | `data class PercentageBased : `[`ChaosPolicy`](./index.md)<br>Applies n% of the time, based on result of a Random. |
