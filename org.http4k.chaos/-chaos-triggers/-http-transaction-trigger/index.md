[http4k](../../../index.md) / [org.http4k.chaos](../../index.md) / [ChaosTriggers](../index.md) / [HttpTransactionTrigger](./index.md)

# HttpTransactionTrigger

`abstract class HttpTransactionTrigger : `[`SerializableTrigger`](../../-serializable-trigger/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L68)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HttpTransactionTrigger(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Inherited Properties

| Name | Summary |
|---|---|
| [type](../../-serializable-trigger/type.md) | `val type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `open operator fun invoke(clock: Clock): `[`ChaosTrigger`](../../-chaos-trigger.md) |
| [matcher](matcher.md) | `abstract fun matcher(): Matcher<`[`HttpTransaction`](../../../org.http4k.core/-http-transaction/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [MatchRequest](../-match-request/index.md) | `data class MatchRequest : `[`HttpTransactionTrigger`](./index.md)<br>Activates when matching attributes of a single received request are met. |
| [MatchResponse](../-match-response/index.md) | `data class MatchResponse : `[`HttpTransactionTrigger`](./index.md)<br>Activates when matching attributes of a single sent response are met. |
