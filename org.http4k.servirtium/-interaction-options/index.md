[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionOptions](./index.md)

# InteractionOptions

`interface InteractionOptions`

General controls for the Servirtium interactions and how they are recorded to the storage format. The
manipulations are used to replace/remove any dynamic parts of the request (eg. "Date" header) so that the
traffic can be correctly matched during the replay process.

### Functions

| Name | Summary |
|---|---|
| [debugTraffic](debug-traffic.md) | Turn on/off the printing of raw HTTP traffic to the console.`open fun debugTraffic(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBinary](is-binary.md) | Determine if the content type from a message should be treated as binary.`open fun isBinary(contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [modify](modify.md) | Modify received requests before they are stored. Use this to replace/remove dynamic parts of the message before serialisation.`open fun modify(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>Modify received responses before they are stored. Use this to replace/remove dynamic parts of the message before serialisation.`open fun modify(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [Defaults](-defaults.md) | By default, no modifications are made to the raw traffic before it gets output to disk. This will not be used very often as dynamic headers such as "Date" and "User-Agent" will almost always be present and need to be stripped out.`val Defaults: `[`InteractionOptions`](./index.md) |
