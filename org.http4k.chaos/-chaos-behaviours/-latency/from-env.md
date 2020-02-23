[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [Latency](index.md) / [fromEnv](./from-env.md)

# fromEnv

`fun fromEnv(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ofMillis(100), defaultMax: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`Behaviour`](../../-behaviour.md)

Get a latency range from the environment.
Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms

