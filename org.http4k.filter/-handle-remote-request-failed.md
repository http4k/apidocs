[http4k](../index.md) / [org.http4k.filter](index.md) / [HandleRemoteRequestFailed](./-handle-remote-request-failed.md)

# HandleRemoteRequestFailed

`fun `[`ServerFilters`](-server-filters/index.md)`.HandleRemoteRequestFailed(exceptionToBody: `[`RemoteRequestFailed`](../org.http4k.cloudnative/-remote-request-failed/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Throwable::getLocalizedMessage): `[`Filter`](../org.http4k.core/-filter/index.md)

Handle exceptions from remote calls and convert them into sensible server-side errors.
Optionally pass in a function to format the response body from the exception.

`fun `[`ClientFilters`](-client-filters/index.md)`.HandleRemoteRequestFailed(responseWasSuccessful: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { status.successful }, responseToMessage: `[`Response`](../org.http4k.core/-response/index.md)`.() -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = Response::bodyString): `[`Filter`](../org.http4k.core/-filter/index.md)

Convert errors from remote calls into exceptions which can be handled at a higher level.
Optionally pass in:

1. a function to determine which responses are successful - defaults to status 200..299
2. a function to format the exception message from the response.
