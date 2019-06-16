[http4k](../../index.md) / [org.http4k.testing](../index.md) / [XmlApprovalTest](./index.md)

# XmlApprovalTest

`class XmlApprovalTest : `[`ContentTypeAwareApprovalTest`](../-content-type-aware-approval-test/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L107)

Approval JUnit5 extension configured to compare prettified-XML messages.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `XmlApprovalTest()`<br>Approval JUnit5 extension configured to compare prettified-XML messages. |

### Functions

| Name | Summary |
|---|---|
| [format](format.md) | `fun format(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Inherited Functions

| Name | Summary |
|---|---|
| [approverFor](../-content-type-aware-approval-test/approver-for.md) | `open fun approverFor(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Approver`](../-approver/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
