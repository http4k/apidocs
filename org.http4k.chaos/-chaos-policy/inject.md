[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicy](index.md) / [inject](./inject.md)

# inject

`open fun inject(behaviour: `[`ChaosBehaviour`](../-chaos-behaviour/index.md)`): `[`ChaosStage`](../-chaos-stage/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicy.kt#L18)

Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the
passed transaction.

