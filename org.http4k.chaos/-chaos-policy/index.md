[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosPolicy](./index.md)

# ChaosPolicy

`interface ChaosPolicy` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicy.kt#L8)

### Functions

| Name | Summary |
|---|---|
| [shouldInject](should-inject.md) | `open fun shouldInject(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun shouldInject(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Always](-always.md) | `fun Always(injectRequest: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true, injectResponse: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): `[`ChaosPolicy`](./index.md) |
| [PercentageBased](-percentage-based.md) | `fun PercentageBased(injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, selector: `[`Random`](http://docs.oracle.com/javase/6/docs/api/java/util/Random.html)` = ThreadLocalRandom.current()): `[`ChaosPolicy`](./index.md) |
| [PercentageBasedFromEnv](-percentage-based-from-env.md) | `fun PercentageBasedFromEnv(): `[`ChaosPolicy`](./index.md) |
