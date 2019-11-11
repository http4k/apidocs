[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [RemoteRequestFailed](./index.md)

# RemoteRequestFailed

`open class RemoteRequestFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/RemoteRequestFailed.kt#L17)

This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a
non-successful status code which caused us to stop processing. They are designed to be used with the
Server and Client filters which will allow automatic handling and propagation of erroneous responses from
upstream.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RemoteRequestFailed(status: `[`Status`](../../org.http4k.core/-status/index.md)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null)`<br>This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a non-successful status code which caused us to stop processing. They are designed to be used with the Server and Client filters which will allow automatic handling and propagation of erroneous responses from upstream. |

### Properties

| Name | Summary |
|---|---|
| [status](status.md) | `val status: `[`Status`](../../org.http4k.core/-status/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [ClientTimeout](../-client-timeout/index.md) | `class ClientTimeout : `[`RemoteRequestFailed`](./index.md) |
| [Forbidden](../-forbidden/index.md) | `class Forbidden : `[`RemoteRequestFailed`](./index.md) |
| [GatewayTimeout](../-gateway-timeout/index.md) | `class GatewayTimeout : `[`RemoteRequestFailed`](./index.md) |
| [NotFound](../-not-found/index.md) | `class NotFound : `[`RemoteRequestFailed`](./index.md) |
| [Unauthorized](../-unauthorized/index.md) | `class Unauthorized : `[`RemoteRequestFailed`](./index.md) |
