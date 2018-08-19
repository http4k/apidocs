[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [Latency](./index.md)

# Latency

`object Latency` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L31)

Blocks the thread for a random amount of time within the allocated range.

### Functions

| Name | Summary |
|---|---|
| [fromEnv](from-env.md) | `fun fromEnv(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: Duration = Duration.ofMillis(100), defaultMax: Duration = Duration.ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`ChaosBehaviour`](../../-chaos-behaviour.md)<br>Get a latency range from the environment. Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms |
| [invoke](invoke.md) | `operator fun invoke(min: Duration = ofMillis(100), max: Duration = ofMillis(500)): `[`ChaosBehaviour`](../../-chaos-behaviour.md) |
