[http4k](../../index.md) / [org.http4k.filter](../index.md) / [OpenTelemetryMetrics](index.md) / [RequestTimer](./-request-timer.md)

# RequestTimer

`fun RequestTimer(meter: Meter = Http4kOpenTelemetry.meter, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.timerDescription.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaults.timerDescription.second, labeler: `[`HttpTransactionLabeler`](../-http-transaction-labeler.md)` = defaults.labeler, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = systemUTC()): `[`Filter`](../../org.http4k.core/-filter.md)