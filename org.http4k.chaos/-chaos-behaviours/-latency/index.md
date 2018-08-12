[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosBehaviours](../index.md) / [Latency](./index.md)

# Latency

`data class Latency : `[`SerializableBehaviour`](../../-serializable-behaviour/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviours.kt#L28)

Blocks the thread for a random amount of time within the allocated range.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Latency(latencyRange: `[`ClosedRange`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)`<Duration>)``Latency(min: Duration = ofMillis(100), max: Duration = ofMillis(500))`<br>Blocks the thread for a random amount of time within the allocated range. |

### Inherited Properties

| Name | Summary |
|---|---|
| [type](../../-serializable-behaviour/type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(tx: `[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`): `[`Response`](../../../org.http4k.core/-response/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [fromEnv](from-env.md) | `fun fromEnv(env: (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = System::getenv, defaultMin: Duration = Duration.ofMillis(100), defaultMax: Duration = Duration.ofMillis(500), minName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MIN", maxName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "CHAOS_LATENCY_MS_MAX"): `[`Latency`](./index.md)<br>Get a latency range from the environment. Defaults to CHAOS_LATENCY_MS_MIN/MAX and a value of 100ms -&gt; 500ms |
