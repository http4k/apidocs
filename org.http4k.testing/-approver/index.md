[http4k](../../index.md) / [org.http4k.testing](../index.md) / [Approver](./index.md)

# Approver

`interface Approver` [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-approval/src/main/kotlin/org/http4k/testing/Approver.kt#L14)

Coordinates the comparison of the content for a test.

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `abstract operator fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> invoke(fn: () -> `[`T`](invoke.md#T)`): `[`T`](invoke.md#T) |

### Extension Functions

| Name | Summary |
|---|---|
| [invoke](../invoke.md) | `operator fun <T : `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`> `[`Approver`](./index.md)`.invoke(baseMatcher: Matcher<`[`T`](../invoke.md#T)`>, fn: () -> `[`T`](../invoke.md#T)`): `[`T`](../invoke.md#T)<br>`operator fun `[`Approver`](./index.md)`.invoke(status: `[`Status`](../../org.http4k.core/-status/index.md)`, fn: () -> `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [NamedResourceApprover](../-named-resource-approver/index.md) | `class NamedResourceApprover : `[`Approver`](./index.md) |
