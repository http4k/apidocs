[http4k](../index.md) / [org.http4k.cloudnative](./index.md)

## Package org.http4k.cloudnative

### Types

| Name | Summary |
|---|---|
| [Http4kK8sServer](-http4k-k8s-server/index.md) | `class Http4kK8sServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md)<br>A K8S server consists of a main application and a health application, running on 2 different ports. This class provides unified start/stop control. |

### Exceptions

| Name | Summary |
|---|---|
| [BadGateway](-bad-gateway/index.md) | `class BadGateway : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [BadRequest](-bad-request/index.md) | `class BadRequest : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [ClientTimeout](-client-timeout/index.md) | `class ClientTimeout : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [Conflict](-conflict/index.md) | `class Conflict : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [InternalServerError](-internal-server-error/index.md) | `class InternalServerError : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [NotFound](-not-found/index.md) | `class NotFound : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [ServiceUnavailable](-service-unavailable/index.md) | `class ServiceUnavailable : `[`UpstreamRequestFailed`](-upstream-request-failed/index.md) |
| [UpstreamRequestFailed](-upstream-request-failed/index.md) | `open class UpstreamRequestFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html)<br>This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a non-successful status code which caused us to stop processing. They are designed to be used with the Server and Client filters which will allow automatic handling and propagation of erroneous responses from upstream. |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |
