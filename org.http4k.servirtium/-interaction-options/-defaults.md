[http4k](../../index.md) / [org.http4k.servirtium](../index.md) / [InteractionOptions](index.md) / [Defaults](./-defaults.md)

# Defaults

`object Defaults : `[`InteractionOptions`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/servirtium/InteractionOptions.kt#L42)

By default, no modifications are made to the raw traffic before it gets output to disk. This will
not be used very often as dynamic headers such as "Date" and "User-Agent" will almost always be present and
need to be stripped out.

### Inherited Functions

| Name | Summary |
|---|---|
| [debugTraffic](debug-traffic.md) | `open fun debugTraffic(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Turn on/off the printing of raw HTTP traffic to the console. |
| [isBinary](is-binary.md) | `open fun isBinary(contentType: `[`ContentType`](../../org.http4k.core/-content-type/index.md)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Determine if the content type from a message should be treated as binary. |
| [modify](modify.md) | `open fun modify(request: `[`Request`](../../org.http4k.core/-request/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>Modify received requests before they are stored. Use this to replace/remove dynamic parts of the message before serialisation.`open fun modify(response: `[`Response`](../../org.http4k.core/-response/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md)<br>Modify received responses before they are stored. Use this to replace/remove dynamic parts of the message before serialisation. |
