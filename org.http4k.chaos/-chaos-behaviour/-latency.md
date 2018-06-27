[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosBehaviour](index.md) / [Latency](./-latency.md)

# Latency

`fun Latency(latencyRange: `[`ClosedRange`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.ranges/-closed-range/index.html)`<Duration> = ofMillis(100)..ofMillis(500)): `[`ChaosBehaviour`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosBehaviour.kt#L27)

Blocks the thread for a random amount of time within the allocated range.

