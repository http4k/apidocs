[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ContentTypeAwareApprovalTest](./index.md)

# ContentTypeAwareApprovalTest

`abstract class ContentTypeAwareApprovalTest : `[`BaseApprovalTest`](../-base-approval-test/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/ApprovalTest.kt#L60)

Approval testing JUnit5 extension that checks the expected content type is present in the

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ContentTypeAwareApprovalTest(contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`, testNamer: `[`TestNamer`](../-test-namer/index.md)` = ClassAndMethod, approvalSource: `[`ApprovalSource`](../-approval-source/index.md)` = FileSystemApprovalSource(File("src/test/resources")))`<br>Approval testing JUnit5 extension that checks the expected content type is present in the |

### Functions

| Name | Summary |
|---|---|
| [approverFor](approver-for.md) | `open fun approverFor(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Approver`](../-approver/index.md) |
| [format](format.md) | `abstract fun format(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [beforeTestExecution](../-base-approval-test/before-test-execution.md) | `open fun beforeTestExecution(context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](../-base-approval-test/resolve-parameter.md) | `open fun resolveParameter(parameterContext: `[`ParameterContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [supportsParameter](../-base-approval-test/supports-parameter.md) | `open fun supportsParameter(parameterContext: `[`ParameterContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, context: `[`ExtensionContext`](https://junit.org/junit5/docs/5.4.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [HtmlApprovalTest](../-html-approval-test/index.md) | `class HtmlApprovalTest : `[`ContentTypeAwareApprovalTest`](./index.md)<br>Approval JUnit5 extension configured to compare prettified-HTML messages. Note that this strips |
| [JsonApprovalTest](../-json-approval-test/index.md) | `class JsonApprovalTest : `[`ContentTypeAwareApprovalTest`](./index.md)<br>Approval JUnit5 extension configured to compare prettified-JSON messages. |
| [XmlApprovalTest](../-xml-approval-test/index.md) | `class XmlApprovalTest : `[`ContentTypeAwareApprovalTest`](./index.md)<br>Approval JUnit5 extension configured to compare prettified-XML messages. |
