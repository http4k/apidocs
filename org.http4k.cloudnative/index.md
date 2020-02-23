[http4k](../index.md) / [org.http4k.cloudnative](./index.md)

## Package org.http4k.cloudnative

### Types

| Name | Summary |
|---|---|
| [Http4kK8sServer](-http4k-k8s-server/index.md) | A K8S server consists of a main application and a health application, running on 2 different ports. This class provides unified start/stop control.`class Http4kK8sServer : `[`Http4kServer`](../org.http4k.server/-http4k-server/index.md) |
| [UpstreamRequestFailed](-upstream-request-failed.md) | `typealias ~~UpstreamRequestFailed~~ = `[`RemoteRequestFailed`](-remote-request-failed/index.md) |

### Exceptions

| Name | Summary |
|---|---|
| [ClientTimeout](-client-timeout/index.md) | `class ClientTimeout : `[`RemoteRequestFailed`](-remote-request-failed/index.md) |
| [Forbidden](-forbidden/index.md) | `class Forbidden : `[`RemoteRequestFailed`](-remote-request-failed/index.md) |
| [GatewayTimeout](-gateway-timeout/index.md) | `class GatewayTimeout : `[`RemoteRequestFailed`](-remote-request-failed/index.md) |
| [NotFound](-not-found/index.md) | `class NotFound : `[`RemoteRequestFailed`](-remote-request-failed/index.md) |
| [RemoteRequestFailed](-remote-request-failed/index.md) | This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a non-successful status code which caused us to stop processing. They are designed to be used with the Server and Client filters which will allow automatic handling and propagation of erroneous responses from upstream.`open class RemoteRequestFailed : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [Unauthorized](-unauthorized/index.md) | `class Unauthorized : `[`RemoteRequestFailed`](-remote-request-failed/index.md) |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [kotlin.Function1](kotlin.-function1/index.md) |  |
