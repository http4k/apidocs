[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [ReportHttpTransaction](./index.md)

# ReportHttpTransaction

`object ReportHttpTransaction`

General reporting Filter for an ReportHttpTransaction. Pass an optional HttpTransactionLabeller to
create custom labels.
This is useful for logging metrics. Note that the passed function blocks the response from completing.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC(), transactionLabeller: `[`HttpTransactionLabeller`](../../-http-transaction-labeller.md)` = { it }, recordFn: (`[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter/index.md) |
