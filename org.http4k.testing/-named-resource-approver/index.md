[http4k](../../index.md) / [org.http4k.testing](../index.md) / [NamedResourceApprover](./index.md)

# NamedResourceApprover

`class NamedResourceApprover : `[`Approver`](../-approver/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/Approver.kt#L18)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `NamedResourceApprover(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, approvalContent: `[`ApprovalContent`](../-approval-content/index.md)`, approvalSource: `[`ApprovalSource`](../-approval-source/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(fn: () -> `[`T`](invoke.md#T)`): `[`T`](invoke.md#T) |

### Extension Functions

| Name | Summary |
|---|---|
| [invoke](../invoke.md) | `operator fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](../-approver/index.md)`.invoke(baseMatcher: Matcher<`[`T`](../invoke.md#T)`>, fn: () -> `[`T`](../invoke.md#T)`): `[`T`](../invoke.md#T)<br>`operator fun `[`Approver`](../-approver/index.md)`.invoke(status: `[`Status`](../../org.http4k.core/-status/index.md)`, fn: () -> `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |
