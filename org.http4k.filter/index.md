[http4k](../index.md) / [org.http4k.filter](./index.md)

## Package org.http4k.filter

This is the base package for all Filter implementations.

### Types

| Name | Summary |
|---|---|
| [CacheControlHeaderPart](-cache-control-header-part/index.md) | `open class CacheControlHeaderPart` |
| [CachingFilters](-caching-filters/index.md) | `object CachingFilters`<br>Useful filters for applying Cache-Controls to request/responses |
| [CanonicalPayload](-canonical-payload/index.md) | `data class CanonicalPayload` |
| [ClientFilters](-client-filters/index.md) | `object ClientFilters` |
| [CorsPolicy](-cors-policy/index.md) | `data class CorsPolicy` |
| [DebuggingFilters](-debugging-filters/index.md) | `object DebuggingFilters` |
| [DefaultCacheTimings](-default-cache-timings/index.md) | `data class DefaultCacheTimings` |
| [GenerateDataClasses](-generate-data-classes/index.md) | `class GenerateDataClasses<out NODE> : `[`Filter`](../org.http4k.core/-filter/index.md)<br>This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GenerateXmlDataClasses](-generate-xml-data-classes/index.md) | `class GenerateXmlDataClasses<NODE : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> : `[`Filter`](../org.http4k.core/-filter/index.md)<br>This Filter is used to generate Data class definitions from a Response containing XML. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields). |
| [GsonGenerateXmlDataClasses](-gson-generate-xml-data-classes/index.md) | `object GsonGenerateXmlDataClasses`<br>Provides an implementation of GenerateXmlDataClasses using GSON as an engine. |
| [JacksonXmlGenerateXmlDataClasses](-jackson-xml-generate-xml-data-classes/index.md) | `object JacksonXmlGenerateXmlDataClasses`<br>Provides an implementation of GenerateXmlDataClasses using GSON as an engine. |
| [MaxAgeTtl](-max-age-ttl/index.md) | `data class MaxAgeTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [MetricFilters](-metric-filters/index.md) | `object MetricFilters` |
| [Payload](-payload/index.md) | `object Payload` |
| [RequestFilters](-request-filters/index.md) | `object RequestFilters` |
| [ResilienceFilters](-resilience-filters/index.md) | `object ResilienceFilters` |
| [ResponseFilters](-response-filters/index.md) | `object ResponseFilters` |
| [SamplingDecision](-sampling-decision/index.md) | `data class SamplingDecision` |
| [ServerFilters](-server-filters/index.md) | `object ServerFilters` |
| [StaleIfErrorTtl](-stale-if-error-ttl/index.md) | `data class StaleIfErrorTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [StaleWhenRevalidateTtl](-stale-when-revalidate-ttl/index.md) | `data class StaleWhenRevalidateTtl : `[`CacheControlHeaderPart`](-cache-control-header-part/index.md) |
| [TraceId](-trace-id/index.md) | `data class TraceId` |
| [TrafficFilters](-traffic-filters/index.md) | `object TrafficFilters` |
| [ZipkinTraces](-zipkin-traces/index.md) | `data class ZipkinTraces` |

### Type Aliases

| Name | Summary |
|---|---|
| [HttpTransactionLabeller](-http-transaction-labeller.md) | `typealias HttpTransactionLabeller = (`[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md)`) -> `[`HttpTransaction`](../org.http4k.core/-http-transaction/index.md) |

### Functions

| Name | Summary |
|---|---|
| [AwsAuth](-aws-auth.md) | `fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentials: `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: Clock = Clock.systemDefaultZone(), payloadMode: `[`Payload.Mode`](-payload/-mode/index.md)` = Payload.Mode.Signed): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Sign AWS requests using static credentials.`fun `[`ClientFilters`](-client-filters/index.md)`.AwsAuth(scope: `[`AwsCredentialScope`](../org.http4k.aws/-aws-credential-scope/index.md)`, credentialsProvider: () -> `[`AwsCredentials`](../org.http4k.aws/-aws-credentials/index.md)`, clock: Clock = Clock.systemDefaultZone(), payloadMode: `[`Payload.Mode`](-payload/-mode/index.md)` = Payload.Mode.Signed): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Sign AWS requests using dynamically provided (expiring) credentials. |
| [gunzipped](gunzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gunzipped(): `[`Body`](../org.http4k.core/-body/index.md) |
| [gzipped](gzipped.md) | `fun `[`Body`](../org.http4k.core/-body/index.md)`.gzipped(): `[`Body`](../org.http4k.core/-body/index.md) |
| [HandleUpstreamRequestFailed](-handle-upstream-request-failed.md) | `fun `[`ServerFilters`](-server-filters/index.md)`.HandleUpstreamRequestFailed(exceptionToBody: `[`UpstreamRequestFailed`](../org.http4k.cloudnative/-upstream-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { localizedMessage }): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Handle exceptions from upstream calls and convert them into sensible server-side errors. Optionally pass in a function to format the response body from the exception.`fun `[`ClientFilters`](-client-filters/index.md)`.HandleUpstreamRequestFailed(responseWasSuccessful: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Convert upstream errors from upstream into exceptions which can be handled at a higher level. Optionally pass in: |
| [ProcessFiles](-process-files.md) | `fun `[`ServerFilters`](-server-filters/index.md)`.ProcessFiles(fileConsumer: (`[`MultipartEntity.File`](../org.http4k.core/-multipart-entity/-file/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Filter`](../org.http4k.core/-filter/index.md)<br>Process files on upload using the passed consumer, which returns a reference. The form file is replaced in the form with this reference. |
