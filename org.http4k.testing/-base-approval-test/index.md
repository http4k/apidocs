[http4k](../../index.md) / [org.http4k.testing](../index.md) / [BaseApprovalTest](./index.md)

# BaseApprovalTest

`interface BaseApprovalTest : BeforeTestExecutionCallback, ParameterResolver`

Base JUnit extension for injecting an Approver into a JUnit5 test-case. Implement this
to provide custom approval behaviours, or

### Functions

| Name | Summary |
|---|---|
| [approverFor](approver-for.md) | `abstract fun approverFor(context: ExtensionContext): `[`Approver`](../-approver/index.md) |
| [beforeTestExecution](before-test-execution.md) | `open fun beforeTestExecution(context: ExtensionContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](resolve-parameter.md) | `open fun resolveParameter(parameterContext: ParameterContext, context: ExtensionContext): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [supportsParameter](supports-parameter.md) | `open fun supportsParameter(parameterContext: ParameterContext, context: ExtensionContext): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ApprovalTest](../-approval-test/index.md) | Standard Approval JUnit5 extension. Can be used to compare any HttpMessages.`class ApprovalTest : `[`BaseApprovalTest`](./index.md) |
| [ContentTypeAwareApprovalTest](../-content-type-aware-approval-test/index.md) | Approval testing JUnit5 extension that checks the expected content type is present in the`abstract class ContentTypeAwareApprovalTest : `[`BaseApprovalTest`](./index.md) |
