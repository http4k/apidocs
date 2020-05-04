[http4k](../../index.md) / [org.http4k.testing](../index.md) / [Approver](./index.md)

# Approver

`interface Approver`

Coordinates the comparison of the content for a test.

### Functions

| Name | Summary |
|---|---|
| [assertApproved](assert-approved.md) | Check the content of the passed message against the previously approved content.`abstract fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> assertApproved(httpMessage: T): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [assertApproved](../assert-approved.md) | `fun `[`Approver`](./index.md)`.assertApproved(response: `[`Response`](../../org.http4k.core/-response/index.md)`, expectedStatus: `[`Status`](../../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`Approver`](./index.md)`.assertApproved(content: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`Approver`](./index.md)`.assertApproved(content: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [hasApprovedContent](../has-approved-content.md) | Create a Hamkrest Matcher for this message that can be combined with other Matchers`fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](./index.md)`.hasApprovedContent(): Matcher<T>` |

### Inheritors

| Name | Summary |
|---|---|
| [NamedResourceApprover](../-named-resource-approver/index.md) | `class NamedResourceApprover : `[`Approver`](./index.md) |
