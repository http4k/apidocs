[http4k](../index.md) / [org.http4k.testing](./index.md)

## Package org.http4k.testing

Useful tools for testing http4k applications.

### Types

| Name | Summary |
|---|---|
| [ApprovalContent](-approval-content/index.md) | `interface ApprovalContent`<br>Determines which parts of the HttpMessage will be compared. |
| [ApprovalSource](-approval-source/index.md) | `interface ApprovalSource`<br>The backing store where the approved and actual content will be stored. |
| [ApprovalTest](-approval-test/index.md) | `class ApprovalTest : `[`BaseApprovalTest`](-base-approval-test/index.md)<br>Standard Approval JUnit5 extension. Can be used to compare any HttpMessages. |
| [Approver](-approver/index.md) | `interface Approver`<br>Coordinates the comparison of the content for a test. |
| [BaseApprovalTest](-base-approval-test/index.md) | `interface BaseApprovalTest : BeforeTestExecutionCallback, ParameterResolver`<br>Base JUnit extension for injecting an Approver into a JUnit5 test-case. Implement this to provide custom approval behaviours, or |
| [FileSystemApprovalSource](-file-system-approval-source/index.md) | `class FileSystemApprovalSource : `[`ApprovalSource`](-approval-source/index.md) |
| [JsonApprovalTest](-json-approval-test/index.md) | `class JsonApprovalTest : `[`BaseApprovalTest`](-base-approval-test/index.md)<br>Approval JUnit5 extension configured to compare prettified-JSON messages. |
| [NamedResourceApprover](-named-resource-approver/index.md) | `class NamedResourceApprover : `[`Approver`](-approver/index.md) |
| [ReadResource](-read-resource/index.md) | `interface ReadResource` |
| [ReadWriteResource](-read-write-resource/index.md) | `interface ReadWriteResource : `[`ReadResource`](-read-resource/index.md) |
| [RecordingEvents](-recording-events/index.md) | `class RecordingEvents : `[`Events`](../org.http4k.core/-events.md)`, `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<`[`Event`](../org.http4k.core/-event/index.md)`>`<br>Simple recording events that can be used in tests |
| [TestNamer](-test-namer/index.md) | `interface TestNamer`<br>Provides the identification of test case. |
| [TestWsClient](-test-ws-client/index.md) | `class TestWsClient : `[`WsClient`](../org.http4k.websocket/-ws-client/index.md)<br>A class that is used for *offline* testing of a routed Websocket, without starting up a Server. Calls are routed synchronously to the receiving Websocket, and error are propagated to the caller. |

### Exceptions

| Name | Summary |
|---|---|
| [ApprovalFailed](-approval-failed/index.md) | `class ApprovalFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [ClosedWebsocket](-closed-websocket/index.md) | `data class ClosedWebsocket : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> `[`Approver`](-approver/index.md)`.invoke(baseMatcher: Matcher<`[`T`](invoke.md#T)`>, fn: () -> `[`T`](invoke.md#T)`): `[`T`](invoke.md#T)<br>`operator fun `[`Approver`](-approver/index.md)`.invoke(status: `[`Status`](../org.http4k.core/-status/index.md)`, fn: () -> `[`Response`](../org.http4k.core/-response/index.md)`): `[`Response`](../org.http4k.core/-response/index.md) |
| [testWsClient](test-ws-client.md) | `fun `[`PolyHandler`](../org.http4k.websocket/-poly-handler/index.md)`.testWsClient(request: `[`Request`](../org.http4k.core/-request/index.md)`): `[`TestWsClient`](-test-ws-client/index.md)`?` |
