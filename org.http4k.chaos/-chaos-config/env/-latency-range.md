[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosConfig](../index.md) / [env](index.md) / [LatencyRange](./-latency-range.md)

# LatencyRange

`fun LatencyRange(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: Duration = Duration.ofMillis(100), defaultMax: Duration = Duration.ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`ClosedRange`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)`<Duration>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosConfig.kt#L14)

Get a latency range from the environment.
Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms

