[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviour](../index.md) / [Latency](index.md) / [fromEnv](./from-env.md)

# fromEnv

`fun fromEnv(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: Duration = Duration.ofMillis(100), defaultMax: Duration = Duration.ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`ChaosBehaviour`](../index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviour.kt#L43)

Get a latency range from the environment.
Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms
