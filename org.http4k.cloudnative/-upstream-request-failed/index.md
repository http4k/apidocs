[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [UpstreamRequestFailed](./index.md)

# UpstreamRequestFailed

`open class UpstreamRequestFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/UpstreamRequestFailed.kt#L9)

This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a
non-successful status code which caused us to stop processing. They are designed to be used with the
Server and Client filters which will allow automatic handling and propagation of erroneous responses from
upstream.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UpstreamRequestFailed(message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a non-successful status code which caused us to stop processing. They are designed to be used with the Server and Client filters which will allow automatic handling and propagation of erroneous responses from upstream. |

### Inheritors

| Name | Summary |
|---|---|
| [BadGateway](../-bad-gateway/index.md) | `class BadGateway : `[`UpstreamRequestFailed`](./index.md) |
| [BadRequest](../-bad-request/index.md) | `class BadRequest : `[`UpstreamRequestFailed`](./index.md) |
| [ClientTimeout](../-client-timeout/index.md) | `class ClientTimeout : `[`UpstreamRequestFailed`](./index.md) |
| [Conflict](../-conflict/index.md) | `class Conflict : `[`UpstreamRequestFailed`](./index.md) |
| [InternalServerError](../-internal-server-error/index.md) | `class InternalServerError : `[`UpstreamRequestFailed`](./index.md) |
| [NotFound](../-not-found/index.md) | `class NotFound : `[`UpstreamRequestFailed`](./index.md) |
| [ServiceUnavailable](../-service-unavailable/index.md) | `class ServiceUnavailable : `[`UpstreamRequestFailed`](./index.md) |
