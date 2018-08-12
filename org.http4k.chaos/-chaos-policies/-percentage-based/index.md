[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosPolicies](../index.md) / [PercentageBased](./index.md)

# PercentageBased

`data class PercentageBased : `[`ChaosPolicy`](../../-chaos-policy/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosPolicies.kt#L57)

Applies n% of the time, based on result of a Random.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PercentageBased(injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, selector: `[`Random`](http://docs.oracle.com/javase/6/docs/api/java/util/Random.html)` = ThreadLocalRandom.current())`<br>Applies n% of the time, based on result of a Random. |

### Properties

| Name | Summary |
|---|---|
| [injectionFrequency](injection-frequency.md) | `val injectionFrequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [selector](selector.md) | `val selector: `[`Random`](http://docs.oracle.com/javase/6/docs/api/java/util/Random.html) |

### Functions

| Name | Summary |
|---|---|
| [appliesTo](applies-to.md) | `fun appliesTo(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [inject](../../-chaos-policy/inject.md) | `open fun inject(behaviour: `[`ChaosBehaviour`](../../-chaos-behaviour/index.md)`): `[`ChaosStage`](../../-chaos-stage/index.md)<br>Returns a ChaosStage which applies some ChaosBehaviour based upon if the policy applies to the passed transaction. |

### Companion Object Functions

| Name | Summary |
|---|---|
| [fromEnvironment](from-environment.md) | `fun fromEnvironment(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultPercentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 50, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_PERCENTAGE"): `[`PercentageBased`](./index.md)<br>Get a percentage from the environment. Defaults to CHAOS_PERCENTAGE and a value of 50% |
