[http4k](../index.md) / [org.http4k.filter](index.md) / [HandleUpstreamRequestFailed](./-handle-upstream-request-failed.md)

# HandleUpstreamRequestFailed

`fun `[`ServerFilters`](-server-filters/index.md)`.HandleUpstreamRequestFailed(exceptionToBody: `[`UpstreamRequestFailed`](../org.http4k.cloudnative/-upstream-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { localizedMessage }): `[`Filter`](../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/filter/cloudnativeExt.kt#L19)

Handle exceptions from upstream calls and convert them into sensible server-side errors.
Optionally pass in a function to format the response body from the exception.

`fun `[`ClientFilters`](-client-filters/index.md)`.HandleUpstreamRequestFailed(notFoundIsAcceptable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true, responseToMessage: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): `[`Filter`](../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/filter/cloudnativeExt.kt#L43)

Convert upstream errors from upstream into exceptions which can be handled at a higher level.
Optionally pass in a function to format the exception message from the response.

