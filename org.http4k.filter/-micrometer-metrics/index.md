[http4k](../../index.md) / [org.http4k.filter](../index.md) / [MicrometerMetrics](./index.md)

# MicrometerMetrics

`class MicrometerMetrics`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MicrometerMetrics(defaults: `[`MetricsDefaults`](../../org.http4k.metrics/-metrics-defaults/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [RequestCounter](-request-counter.md) | `fun RequestCounter(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.counterDescription.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.counterDescription.second, labeler: `[`HttpTransactionLabeler`](../-http-transaction-labeler.md)` = defaults.labeler, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter.md) |
| [RequestTimer](-request-timer.md) | `fun RequestTimer(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.timerDescription.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.timerDescription.second, labeler: `[`HttpTransactionLabeler`](../-http-transaction-labeler.md)` = defaults.labeler, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`Filter`](../../org.http4k.core/-filter.md) |
