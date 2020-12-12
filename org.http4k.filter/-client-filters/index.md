[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](./index.md)

# ClientFilters

`object ClientFilters`

### Types

| Name | Summary |
|---|---|
| [BasicAuth](-basic-auth/index.md) | `object BasicAuth` |
| [BearerAuth](-bearer-auth/index.md) | `object BearerAuth` |
| [Cookies](-cookies/index.md) | `object Cookies` |
| [CustomBasicAuth](-custom-basic-auth/index.md) | `object CustomBasicAuth` |
| [FollowRedirects](-follow-redirects/index.md) | `object FollowRedirects` |
| [ProxyBasicAuth](-proxy-basic-auth/index.md) | `object ProxyBasicAuth` |

### Functions

| Name | Summary |
|---|---|
| [AcceptGZip](-accept-g-zip.md) | Support for GZipped responses from clients.`fun AcceptGZip(compressionMode: `[`GzipCompressionMode`](../-gzip-compression-mode/index.md)` = Memory): `[`Filter`](../../org.http4k.core/-filter.md) |
| [ApiKeyAuth](-api-key-auth.md) | `fun ApiKeyAuth(set: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Filter`](../../org.http4k.core/-filter.md) |
| [CleanProxy](-clean-proxy.md) | This Filter is used to clean the Request and Response when proxying directly to another system. The purpose of this is to remove any routing metadata that we may have attached to it before sending it onwards.`fun CleanProxy(): <ERROR CLASS>` |
| [GZip](-g-zip.md) | Basic GZip and Gunzip support of Request/Response. Only Gunzip responses when the response contains "transfer-encoding" header containing 'gzip'`fun GZip(compressionMode: `[`GzipCompressionMode`](../-gzip-compression-mode/index.md)` = Memory): `[`Filter`](../../org.http4k.core/-filter.md) |
| [RequestTracing](-request-tracing.md) | Adds Zipkin request tracing headers to the outbound request. (traceid, spanid, parentspanid)`fun RequestTracing(startReportFn: (`[`Request`](../../org.http4k.core/-request/index.md)`, `[`ZipkinTraces`](../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _ -> }, endReportFn: (`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Response`](../../org.http4k.core/-response/index.md)`, `[`ZipkinTraces`](../-zipkin-traces/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)` = { _, _, _ -> }): `[`Filter`](../../org.http4k.core/-filter.md) |
| [SetBaseUriFrom](-set-base-uri-from.md) | Sets the base uri (host + base path) on an outbound request. This is useful to separate configuration of remote endpoints from the logic required to construct the rest of the request.`fun SetBaseUriFrom(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../org.http4k.core/-filter.md) |
| [SetHostFrom](-set-host-from.md) | Sets the host on an outbound request. This is useful to separate configuration of remote endpoints from the logic required to construct the rest of the request.`fun SetHostFrom(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Filter`](../../org.http4k.core/-filter.md) |
| [SetXForwardedHost](-set-x-forwarded-host.md) | Copy the Host header into the x-forwarded-host header of a request. Used when we are using proxies to divert traffic to another server.`fun SetXForwardedHost(): <ERROR CLASS>` |

### Extension Properties

| Name | Summary |
|---|---|
| [MicrometerMetrics](../-micrometer-metrics.md) | `val `[`ClientFilters`](./index.md)`.MicrometerMetrics: `[`MicrometerMetrics`](../-micrometer-metrics/index.md) |
| [OpenTelemetryMetrics](../-open-telemetry-metrics.md) | `val `[`ClientFilters`](./index.md)`.OpenTelemetryMetrics: `[`OpenTelemetryMetrics`](../-open-telemetry-metrics/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [AwsAuth](../-aws-auth.md) | Sign AWS requests using static credentials.`fun `[`ClientFilters`](./index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): <ERROR CLASS>`<br>Sign AWS requests using dynamically provided (expiring) credentials.`fun `[`ClientFilters`](./index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../../org.http4k.aws/-aws-credential-scope/index.md)`, credentialsProvider: () -> `[`AwsCredentials`](../../org.http4k.aws/-aws-credentials/index.md)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), payloadMode: Mode = Payload.Mode.Signed): <ERROR CLASS>` |
| [HandleRemoteRequestFailed](../-handle-remote-request-failed.md) | Convert errors from remote calls into exceptions which can be handled at a higher level. Optionally pass in:`fun `[`ClientFilters`](./index.md)`.HandleRemoteRequestFailed(responseWasSuccessful: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): <ERROR CLASS>` |
| [HandleUpstreamRequestFailed](../-handle-upstream-request-failed.md) | `fun `[`ClientFilters`](./index.md)`.~~HandleUpstreamRequestFailed~~(responseWasSuccessful: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): <ERROR CLASS>` |
| [OpenTelemetryTracing](../-open-telemetry-tracing.md) | `fun `[`ClientFilters`](./index.md)`.OpenTelemetryTracing(tracer: Tracer = Http4kOpenTelemetry.tracer, spanNamer: (`[`Request`](../../org.http4k.core/-request/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { it.uri.toString() }, error: (`[`Request`](../../org.http4k.core/-request/index.md)`, `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { _, t -> t.localizedMessage }): `[`Filter`](../../org.http4k.core/-filter.md) |
| [SetAwsServiceUrl](../-set-aws-service-url.md) | `fun `[`ClientFilters`](./index.md)`.SetAwsServiceUrl(serviceNsme: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, region: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../../org.http4k.core/-filter.md) |
