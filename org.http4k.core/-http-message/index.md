[http4k](../../index.md) / [org.http4k.core](../index.md) / [HttpMessage](./index.md)

# HttpMessage

`interface HttpMessage : `[`Closeable`](https://docs.oracle.com/javase/9/docs/api/java/io/Closeable.html)

HttpMessages are designed to be immutable, so any mutation methods return a modified copy of the message.

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `abstract val body: `[`Body`](../-body/index.md) |
| [headers](headers.md) | `abstract val headers: `[`Headers`](../-headers.md) |
| [version](version.md) | `abstract val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | (Copy &amp;) sets the body content.`abstract fun body(body: `[`Body`](../-body/index.md)`): `[`HttpMessage`](./index.md)<br>`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpMessage`](./index.md)<br>`abstract fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null): `[`HttpMessage`](./index.md) |
| [bodyString](body-string.md) | This will realise any underlying stream.`open fun bodyString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [close](close.md) | Closes the request. For server generated messages, this is called by all backend/client implementations, but when consuming external responses in streaming mode, this should be used.`open fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [header](header.md) | Retrieves the first header value with this name.`open fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>(Copy &amp;) Adds a header value with this name.`abstract fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`HttpMessage`](./index.md) |
| [headers](headers.md) | (Copy &amp;) Add all passed headers.`abstract fun headers(headers: `[`Headers`](../-headers.md)`): `[`HttpMessage`](./index.md) |
| [headerValues](header-values.md) | Retrieves all header values with this name.`open fun headerValues(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [removeHeader](remove-header.md) | (Copy &amp;) remove headers with this name.`abstract fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`HttpMessage`](./index.md) |
| [replaceHeader](replace-header.md) | (Copy &amp;) Adds a header value with this name, replacing any previously set values.`abstract fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`HttpMessage`](./index.md) |
| [replaceHeaders](replace-headers.md) | Replace all headers with ones passed.`abstract fun replaceHeaders(source: `[`Headers`](../-headers.md)`): `[`HttpMessage`](./index.md) |
| [toMessage](to-message.md) | Returns a formatted wire representation of this message.`abstract fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [HTTP_1_1](-h-t-t-p_1_1.md) | `const val HTTP_1_1: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [HTTP_2](-h-t-t-p_2.md) | `const val HTTP_2: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [alphabetiseHeaders](../alphabetise-headers.md) | `fun <T : `[`HttpMessage`](./index.md)`> T.alphabetiseHeaders(): T` |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](./index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |

### Inheritors

| Name | Summary |
|---|---|
| [Request](../-request/index.md) | `interface Request : `[`HttpMessage`](./index.md) |
| [Response](../-response/index.md) | `interface Response : `[`HttpMessage`](./index.md) |
