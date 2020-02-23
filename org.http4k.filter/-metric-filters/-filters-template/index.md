[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [MetricFilters](../index.md) / [FiltersTemplate](./index.md)

# FiltersTemplate

`class FiltersTemplate`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FiltersTemplate(defaultTimer: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, defaultCounter: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, defaultLabeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [RequestCounter](-request-counter.md) | `fun RequestCounter(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultCounter.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultCounter.second, labeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = defaultLabeller): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
| [RequestTimer](-request-timer.md) | `fun RequestTimer(meterRegistry: MeterRegistry, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = defaultTimer.first, description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = defaultTimer.second, labeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = defaultLabeller, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC()): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
