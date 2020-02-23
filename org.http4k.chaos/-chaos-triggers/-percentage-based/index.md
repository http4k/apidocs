[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [PercentageBased](./index.md)

# PercentageBased

`object PercentageBased`

Applies n% of the time, based on result of a Random.

### Functions

| Name | Summary |
|---|---|
| [fromEnvironment](from-environment.md) | Get a percentage from the environment. Defaults to CHAOS_PERCENTAGE and a value of 50%`fun fromEnvironment(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultPercentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 50, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_PERCENTAGE"): `[`Trigger`](../../-trigger.md) |
| [invoke](invoke.md) | `operator fun invoke(injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, selector: `[`Random`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.random/-random/index.html)` = Random): `[`Trigger`](../../-trigger.md) |
