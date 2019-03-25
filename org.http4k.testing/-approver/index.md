[http4k](../../index.md) / [org.http4k.testing](../index.md) / [Approver](./index.md)

# Approver

`interface Approver` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/Approver.kt#L16)

Coordinates the comparison of the content for a test.

### Functions

| Name | Summary |
|---|---|
| [assertApproved](assert-approved.md) | `abstract fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> assertApproved(httpMessage: `[`T`](assert-approved.md#T)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Check the content of the passed message against the previously approved content. |

### Extension Functions

| Name | Summary |
|---|---|
| [assertApproved](../assert-approved.md) | `fun `[`Approver`](./index.md)`.assertApproved(response: `[`Response`](../../org.http4k.core/-response/index.md)`, expectedStatus: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [hasApprovedContent](../has-approved-content.md) | `fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](./index.md)`.hasApprovedContent(): Matcher<`[`T`](../has-approved-content.md#T)`>`<br>Create a Hamkrest Matcher for this message that can be combined with other Matchers |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [NamedResourceApprover](../-named-resource-approver/index.md) | `class NamedResourceApprover : `[`Approver`](./index.md) |
