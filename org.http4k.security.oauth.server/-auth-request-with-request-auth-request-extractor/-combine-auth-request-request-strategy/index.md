[http4k](../../../index.md) / [org.http4k.security.oauth.server](../../index.md) / [AuthRequestWithRequestAuthRequestExtractor](../index.md) / [CombineAuthRequestRequestStrategy](./index.md)

# CombineAuthRequestRequestStrategy

`sealed class CombineAuthRequestRequestStrategy`

### Types

| Name | Summary |
|---|---|
| [AuthRequestOnly](-auth-request-only/index.md) | `object AuthRequestOnly : CombineAuthRequestRequestStrategy` |
| [Combine](-combine/index.md) | `object Combine : CombineAuthRequestRequestStrategy` |
| [RequestObjectOnly](-request-object-only/index.md) | `object RequestObjectOnly : CombineAuthRequestRequestStrategy` |

### Functions

| Name | Summary |
|---|---|
| [combine](combine.md) | `abstract fun <T> combine(authRequestValue: T?, requestObjectValue: T?): T?`<br>`abstract fun <T> combine(authRequestValue: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<T>, requestObjectValue: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<T>): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<T>` |
