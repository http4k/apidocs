[http4k](../../index.md) / [org.http4k.chaos](../index.md) / [ChaosTriggers](./index.md)

# ChaosTriggers

`object ChaosTriggers` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-chaos/src/main/kotlin/org/http4k/chaos/ChaosTriggers.kt#L29)

### Types

| Name | Summary |
|---|---|
| [Deadline](-deadline/index.md) | `data class Deadline : `[`SerializableTrigger`](../-serializable-trigger/index.md)<br>Activates after a particular instant in time. |
| [Delay](-delay/index.md) | `data class Delay : `[`SerializableTrigger`](../-serializable-trigger/index.md)<br>Activates after a particular delay (compared to instantiation). |
| [HttpTransactionTrigger](-http-transaction-trigger/index.md) | `abstract class HttpTransactionTrigger : `[`SerializableTrigger`](../-serializable-trigger/index.md)`, Matcher<`[`HttpTransaction`](../../org.http4k.core/-http-transaction/index.md)`>` |
| [MatchRequest](-match-request/index.md) | `data class MatchRequest : `[`HttpTransactionTrigger`](-http-transaction-trigger/index.md) |
| [MatchResponse](-match-response/index.md) | `data class MatchResponse : `[`HttpTransactionTrigger`](-http-transaction-trigger/index.md) |
