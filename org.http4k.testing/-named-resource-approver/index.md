[http4k](../../index.md) / [org.http4k.testing](../index.md) / [NamedResourceApprover](./index.md)

# NamedResourceApprover

`class NamedResourceApprover : `[`Approver`](../-approver/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `NamedResourceApprover(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, approvalContent: `[`ApprovalContent`](../-approval-content/index.md)`, approvalSource: `[`ApprovalSource`](../-approval-source/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [assertApproved](assert-approved.md) | Check the content of the passed message against the previously approved content.`fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> assertApproved(httpMessage: T): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [assertApproved](../assert-approved.md) | `fun `[`Approver`](../-approver/index.md)`.assertApproved(response: `[`Response`](../../org.http4k.core/-response/index.md)`, expectedStatus: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [hasApprovedContent](../has-approved-content.md) | Create a Hamkrest Matcher for this message that can be combined with other Matchers`fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](../-approver/index.md)`.hasApprovedContent(): Matcher<T>` |
