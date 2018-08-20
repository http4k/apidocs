[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosPolicies](../index.md) / [PercentageBased](./index.md)

# PercentageBased

`object PercentageBased` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L73)

Applies n% of the time, based on result of a Random.

### Functions

| Name | Summary |
|---|---|
| [fromEnvironment](from-environment.md) | `fun fromEnvironment(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultPercentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 50, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_PERCENTAGE"): `[`Policy`](../../-policy.md)<br>Get a percentage from the environment. Defaults to CHAOS_PERCENTAGE and a value of 50% |
| [invoke](invoke.md) | `operator fun invoke(injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, selector: `[`Random`](http://docs.oracle.com/javase/6/docs/api/java/util/Random.html)` = ThreadLocalRandom.current()): `[`Policy`](../../-policy.md) |
