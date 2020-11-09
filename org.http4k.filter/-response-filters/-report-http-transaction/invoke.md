[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [ResponseFilters](../index.md) / [ReportHttpTransaction](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemUTC(), transactionLabeler: `[`HttpTransactionLabeler`](../../-http-transaction-labeler.md)` = { it }, recordFn: (`[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Filter`](../../../org.http4k.core/-filter.md)