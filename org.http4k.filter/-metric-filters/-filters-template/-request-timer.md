[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [MetricFilters](../index.md) / [FiltersTemplate](index.md) / [RequestTimer](./-request-timer.md)

# RequestTimer

`fun RequestTimer(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultTimer.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultTimer.second, labeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = defaultLabeller, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`Filter`](../../../org.http4k.core/-filter/index.md)