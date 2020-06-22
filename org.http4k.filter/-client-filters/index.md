[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](./index.md)

# ClientFilters

`object ClientFilters`

### Types

| Name | Summary |
|---|---|
| [AcceptGZip](-accept-g-zip/index.md) | Support for GZipped responses from clients.`object AcceptGZip` |
| [ApiKeyAuth](-api-key-auth/index.md) | `object ApiKeyAuth` |
| [BasicAuth](-basic-auth/index.md) | `object BasicAuth` |
| [BearerAuth](-bearer-auth/index.md) | `object BearerAuth` |
| [CleanProxy](-clean-proxy/index.md) | This Filter is used to clean the Request and Response when proxying directly to another system. The purpose of this is to remove any routing metadata that we may have attached to it before sending it onwards.`object CleanProxy` |
| [Cookies](-cookies/index.md) | `object Cookies` |
| [FollowRedirects](-follow-redirects/index.md) | `object FollowRedirects` |
| [GZip](-g-zip/index.md) | Basic GZip and Gunzip support of Request/Response. Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip'`object GZip` |
| [RequestTracing](-request-tracing/index.md) | Adds Zipkin request tracing headers to the outbound request. (traceid, spanid, parentspanid)`object RequestTracing` |
| [SetBaseUriFrom](-set-base-uri-from/index.md) | Sets the base uri (host + base path) on an outbound request. This is useful to separate configuration of remote endpoints from the logic required to construct the rest of the request.`object SetBaseUriFrom` |
| [SetHostFrom](-set-host-from/index.md) | Sets the host on an outbound request. This is useful to separate configuration of remote endpoints from the logic required to construct the rest of the request.`object SetHostFrom` |

### Extension Functions

| Name | Summary |
|---|---|
| [AwsAuth](../-aws-auth.md) | Sign AWS requests using static credentials.`fun `[`ClientFilters`](./index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>Sign AWS requests using dynamically provided (expiring) credentials.`fun `[`ClientFilters`](./index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../../org.http4k.aws/-aws-credential-scope/index.md)`, credentialsProvider: () -> `[`AwsCredentials`](../../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [HandleRemoteRequestFailed](../-handle-remote-request-failed.md) | Convert errors from remote calls into exceptions which can be handled at a higher level. Optionally pass in:`fun `[`ClientFilters`](./index.md)`.HandleRemoteRequestFailed(responseWasSuccessful: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): `[`Filter`](../../org.http4k.core/-filter/index.md) |
| [HandleUpstreamRequestFailed](../-handle-upstream-request-failed.md) | `fun `[`ClientFilters`](./index.md)`.~~HandleUpstreamRequestFailed~~(responseWasSuccessful: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): `[`Filter`](../../org.http4k.core/-filter/index.md) |
