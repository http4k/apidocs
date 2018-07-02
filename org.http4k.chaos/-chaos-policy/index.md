[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicy](./index.md)

# ChaosPolicy

`interface ChaosPolicy` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicy.kt#L11)

Determines whether or not to apply a particular type of ChaosBehaviour to a request/response.

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](./index.md)<br>Applies to every transaction. |
| [PercentageBased](-percentage-based/index.md) | `object PercentageBased`<br>Applies n% of the time, based on result of a Random. |

### Functions

| Name | Summary |
|---|---|
| [appliesTo](applies-to.md) | `open fun appliesTo(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [inject](inject.md) | `open fun inject(behaviour: `[`ChaosBehaviour`](../-chaos-behaviour/index.md)`): `[`ChaosStage`](../-chaos-stage/index.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Once](-once.md) | `fun Once(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosPolicy`](./index.md)<br>Single application predicated on the ChaosTrigger. Further matches don't apply |
| [Only](-only.md) | `fun Only(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosPolicy`](./index.md)<br>Application predicated on the ChaosTrigger |

### Inheritors

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](./index.md)<br>Applies to every transaction. |
