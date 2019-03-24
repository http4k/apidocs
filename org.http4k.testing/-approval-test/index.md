[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ApprovalTest](./index.md)

# ApprovalTest

`class ApprovalTest : `[`BaseApprovalTest`](../-base-approval-test/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L49)

Standard Approval JUnit5 extension. Can be used to compare any HttpMessages.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ApprovalTest()`<br>Standard Approval JUnit5 extension. Can be used to compare any HttpMessages. |

### Functions

| Name | Summary |
|---|---|
| [approverFor](approver-for.md) | `fun approverFor(context: ExtensionContext): `[`Approver`](../-approver/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [beforeTestExecution](../-base-approval-test/before-test-execution.md) | `open fun beforeTestExecution(context: ExtensionContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](../-base-approval-test/resolve-parameter.md) | `open fun resolveParameter(parameterContext: ParameterContext, context: ExtensionContext): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [supportsParameter](../-base-approval-test/supports-parameter.md) | `open fun supportsParameter(parameterContext: ParameterContext, context: ExtensionContext): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
