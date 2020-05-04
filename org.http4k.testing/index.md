[http4k](../index.md) / [org.http4k.testing](./index.md)

## Package org.http4k.testing

Useful tools for testing http4k applications.

### Types

| Name | Summary |
|---|---|
| [ApprovalContent](-approval-content/index.md) | Determines which parts of the HttpMessage will be compared.`interface ApprovalContent` |
| [ApprovalSource](-approval-source/index.md) | The backing store where the approved and actual content will be stored.`interface ApprovalSource` |
| [ApprovalTest](-approval-test/index.md) | Standard Approval JUnit5 extension. Can be used to compare any HttpMessages.`class ApprovalTest : `[`BaseApprovalTest`](-base-approval-test/index.md) |
| [Approver](-approver/index.md) | Coordinates the comparison of the content for a test.`interface Approver` |
| [BaseApprovalTest](-base-approval-test/index.md) | Base JUnit extension for injecting an Approver into a JUnit5 test-case. Implement this to provide custom approval behaviours, or`interface BaseApprovalTest : BeforeTestExecutionCallback, ParameterResolver` |
| [ContentTypeAwareApprovalTest](-content-type-aware-approval-test/index.md) | Approval testing JUnit5 extension that checks the expected content type is present in the`abstract class ContentTypeAwareApprovalTest : `[`BaseApprovalTest`](-base-approval-test/index.md) |
| [FileSystemApprovalSource](-file-system-approval-source/index.md) | `class FileSystemApprovalSource : `[`ApprovalSource`](-approval-source/index.md) |
| [HtmlApprovalTest](-html-approval-test/index.md) | Approval JUnit5 extension configured to compare prettified-HTML messages. Note that this strips`class HtmlApprovalTest : `[`ContentTypeAwareApprovalTest`](-content-type-aware-approval-test/index.md) |
| [JsonApprovalTest](-json-approval-test/index.md) | Approval JUnit5 extension configured to compare prettified-JSON messages.`class JsonApprovalTest : `[`ContentTypeAwareApprovalTest`](-content-type-aware-approval-test/index.md) |
| [NamedResourceApprover](-named-resource-approver/index.md) | `class NamedResourceApprover : `[`Approver`](-approver/index.md) |
| [ReadResource](-read-resource/index.md) | `interface ReadResource` |
| [ReadWriteResource](-read-write-resource/index.md) | `interface ReadWriteResource : `[`ReadResource`](-read-resource/index.md) |
| [RecordingEvents](-recording-events/index.md) | Simple recording events that can be used in tests`class RecordingEvents : `[`Events`](../org.http4k.events/-events.md)`, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Event`](../org.http4k.events/-event/index.md)`>` |
| [TestNamer](-test-namer/index.md) | Provides the identification of test case.`interface TestNamer` |
| [TestWsClient](-test-ws-client/index.md) | A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls are routed synchronously to the receiving Websocket, and error are propagated to the caller.`class TestWsClient : `[`WsClient`](../org.http4k.websocket/-ws-client/index.md) |
| [XmlApprovalTest](-xml-approval-test/index.md) | Approval JUnit5 extension configured to compare prettified-XML messages.`class XmlApprovalTest : `[`ContentTypeAwareApprovalTest`](-content-type-aware-approval-test/index.md) |

### Exceptions

| Name | Summary |
|---|---|
| [ApprovalFailed](-approval-failed/index.md) | `class ApprovalFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [ClosedWebsocket](-closed-websocket/index.md) | `data class ClosedWebsocket : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [assertApproved](assert-approved.md) | `fun `[`Approver`](-approver/index.md)`.assertApproved(response: `[`Response`](../org.http4k.core/-response/index.md)`, expectedStatus: `[`Status`](../org.http4k.core/-status/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`Approver`](-approver/index.md)`.assertApproved(content: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun `[`Approver`](-approver/index.md)`.assertApproved(content: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [hasApprovedContent](has-approved-content.md) | Create a Hamkrest Matcher for this message that can be combined with other Matchers`fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> `[`Approver`](-approver/index.md)`.hasApprovedContent(): Matcher<T>` |
| [testWsClient](test-ws-client.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.testWsClient(request: `[`Request`](../org.http4k.core/-request/index.md)`): `[`TestWsClient`](-test-ws-client/index.md)`?` |
