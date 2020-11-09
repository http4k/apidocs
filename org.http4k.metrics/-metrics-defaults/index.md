[http4k](../../index.md) / [org.http4k.metrics](../index.md) / [MetricsDefaults](./index.md)

# MetricsDefaults

`data class MetricsDefaults`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MetricsDefaults(counterDescription: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, timerDescription: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, labeler: `[`HttpTransactionLabeler`](../../org.http4k.filter/-http-transaction-labeler.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [counterDescription](counter-description.md) | `val counterDescription: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [labeler](labeler.md) | `val labeler: `[`HttpTransactionLabeler`](../../org.http4k.filter/-http-transaction-labeler.md) |
| [timerDescription](timer-description.md) | `val timerDescription: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [client](client.md) | `val client: `[`MetricsDefaults`](./index.md) |
| [server](server.md) | `val server: `[`MetricsDefaults`](./index.md) |
