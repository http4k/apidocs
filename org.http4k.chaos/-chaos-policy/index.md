[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicy](./index.md)

# ChaosPolicy

`interface ChaosPolicy` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicy.kt#L10)

Determines whether or not to apply a particular type of ChaosBehaviour to a request/response.

### Types

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](./index.md) |

### Functions

| Name | Summary |
|---|---|
| [appliesTo](applies-to.md) | `open fun appliesTo(tx: `[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [inject](inject.md) | `open fun inject(behaviour: `[`ChaosBehaviour`](../-chaos-behaviour/index.md)`): `[`ChaosStage`](../-chaos-stage/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Only](-only.md) | `fun Only(trigger: `[`ChaosTrigger`](../-chaos-trigger.md)`): `[`ChaosPolicy`](./index.md) |
| [PercentageBased](-percentage-based.md) | `fun PercentageBased(injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, selector: `[`Random`](http://docs.oracle.com/javase/6/docs/api/java/util/Random.html)` = ThreadLocalRandom.current()): `[`ChaosPolicy`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [Always](-always/index.md) | `object Always : `[`ChaosPolicy`](./index.md) |
