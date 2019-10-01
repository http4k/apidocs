[http4k](../../index.md) / [org.http4k.testing](../index.md) / [BaseApprovalTest](./index.md)

# BaseApprovalTest

`interface BaseApprovalTest : `[`BeforeTestExecutionCallback`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/BeforeTestExecutionCallback.html)`, `[`ParameterResolver`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterResolver.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L29)

Base JUnit extension for injecting an Approver into a JUnit5 test-case. Implement this
to provide custom approval behaviours, or

### Functions

| Name | Summary |
|---|---|
| [approverFor](approver-for.md) | `abstract fun approverFor(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Approver`](../-approver/index.md) |
| [beforeTestExecution](before-test-execution.md) | `open fun beforeTestExecution(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](resolve-parameter.md) | `open fun resolveParameter(parameterContext: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [supportsParameter](supports-parameter.md) | `open fun supportsParameter(parameterContext: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ApprovalTest](../-approval-test/index.md) | `class ApprovalTest : `[`BaseApprovalTest`](./index.md)<br>Standard Approval JUnit5 extension. Can be used to compare any HttpMessages. |
| [ContentTypeAwareApprovalTest](../-content-type-aware-approval-test/index.md) | `abstract class ContentTypeAwareApprovalTest : `[`BaseApprovalTest`](./index.md)<br>Approval testing JUnit5 extension that checks the expected content type is present in the |
