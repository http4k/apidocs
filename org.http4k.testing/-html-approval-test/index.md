[http4k](../../index.md) / [org.http4k.testing](../index.md) / [HtmlApprovalTest](./index.md)

# HtmlApprovalTest

`class HtmlApprovalTest : `[`ContentTypeAwareApprovalTest`](../-content-type-aware-approval-test/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L99)

Approval JUnit5 extension configured to compare prettified-HTML messages. Note that this strips

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HtmlApprovalTest(testNamer: `[`TestNamer`](../-test-namer/index.md)` = ClassAndMethod, approvalSource: `[`ApprovalSource`](../-approval-source/index.md)` = FileSystemApprovalSource(File("src/test/resources")))`<br>Approval JUnit5 extension configured to compare prettified-HTML messages. Note that this strips |

### Functions

| Name | Summary |
|---|---|
| [format](format.md) | `fun format(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Inherited Functions

| Name | Summary |
|---|---|
| [approverFor](../-content-type-aware-approval-test/approver-for.md) | `open fun approverFor(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.1/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Approver`](../-approver/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
