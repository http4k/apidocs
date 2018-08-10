[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [MatchResponse](./index.md)

# MatchResponse

`data class MatchResponse : `[`HttpTransactionTrigger`](../-http-transaction-trigger/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L76)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MatchResponse(status: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?, headers: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>?, body: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`?)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`?` |
| [headers](headers.md) | `val headers: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`>?` |
| [status](status.md) | `val status: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |

### Inherited Functions

| Name | Summary |
|---|---|
| [invoke](../-http-transaction-trigger/invoke.md) | `open operator fun invoke(clock: Clock): `[`ChaosTrigger`](../../-chaos-trigger.md) |
