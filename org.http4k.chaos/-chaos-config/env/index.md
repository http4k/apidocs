[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosConfig](../index.md) / [env](./index.md)

# env

`object env` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosConfig.kt#L9)

### Functions

| Name | Summary |
|---|---|
| [LatencyRange](-latency-range.md) | `fun LatencyRange(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: Duration = Duration.ofMillis(100), defaultMax: Duration = Duration.ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`ClosedRange`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)`<Duration>`<br>Get a latency range from the environment. Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms |
| [Percentage](-percentage.md) | `fun Percentage(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultPercentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 50, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_PERCENTAGE"): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get a percentage from the environment. Defaults to CHAOS_PERCENTAGE and a value of 50% |
