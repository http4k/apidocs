[http4k](../../index.md) / [org.http4k.testing](../index.md) / [NamedResourceApprover](./index.md)

# NamedResourceApprover

`class NamedResourceApprover : `[`Approver`](../-approver/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/Approver.kt#L24)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `NamedResourceApprover(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, approvalContent: `[`ApprovalContent`](../-approval-content/index.md)`, approvalSource: `[`ApprovalSource`](../-approval-source/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [assertApproved](assert-approved.md) | `fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> assertApproved(httpMessage: `[`T`](assert-approved.md#T)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Check the content of the passed message against the previously approved content. |

### Extension Functions

| Name | Summary |
|---|---|
| [assertApproved](../assert-approved.md) | `fun `[`Approver`](../-approver/index.md)`.assertApproved(response: `[`Response`](../../org.http4k.core/-response/index.md)`, expectedStatus: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [hasApprovedContent](../has-approved-content.md) | `fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](../-approver/index.md)`.hasApprovedContent(): Matcher<`[`T`](../has-approved-content.md#T)`>`<br>Create a Hamkrest Matcher for this message that can be combined with other Matchers |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
