[http4k](../../index.md) / [org.http4k.testing](../index.md) / [JsonApprovalTest](./index.md)

# JsonApprovalTest

`class JsonApprovalTest : `[`BaseApprovalTest`](../-base-approval-test/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L52)

Approval JUnit5 extension configured to compare prettified-JSON messages.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonApprovalTest()`<br>Approval JUnit5 extension configured to compare prettified-JSON messages. |

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
