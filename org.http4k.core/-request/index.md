[http4k](../../index.md) / [org.http4k.core](../index.md) / [Request](./index.md)

# Request

`interface Request : `[`HttpMessage`](../-http-message/index.md)

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `abstract val method: `[`Method`](../-method/index.md) |
| [uri](uri.md) | `abstract val uri: `[`Uri`](../-uri/index.md) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | (Copy &amp;) sets the body content.`abstract fun body(body: `[`Body`](../-body/index.md)`): `[`Request`](./index.md)<br>`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md)<br>`abstract fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Request`](./index.md) |
| [header](header.md) | (Copy &amp;) Adds a header value with this name.`abstract fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md) |
| [headers](headers.md) | (Copy &amp;) Add all passed headers.`abstract fun headers(headers: `[`Headers`](../-headers.md)`): `[`Request`](./index.md) |
| [method](method.md) | (Copy &amp;) sets the method.`abstract fun method(method: `[`Method`](../-method/index.md)`): `[`Request`](./index.md) |
| [queries](queries.md) | Retrieves all query values with this name.`abstract fun queries(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [query](query.md) | (Copy &amp;) Adds a query value with this name.`abstract fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md)<br>Retrieves the first query value with this name.`abstract fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeHeader](remove-header.md) | (Copy &amp;) remove headers with this name.`abstract fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [removeQuery](remove-query.md) | (Copy &amp;) remove queries with this name.`abstract fun removeQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [replaceHeader](replace-header.md) | (Copy &amp;) Adds a header value with this name, replacing any previously set values.`abstract fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md) |
| [replaceHeaders](replace-headers.md) | Replace all headers with ones passed.`abstract fun replaceHeaders(source: `[`Headers`](../-headers.md)`): `[`Request`](./index.md) |
| [toMessage](to-message.md) | Returns a formatted wire representation of this message.`open fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [uri](uri.md) | (Copy &amp;) sets the Uri.`abstract fun uri(uri: `[`Uri`](../-uri/index.md)`): `[`Request`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun invoke(method: `[`Method`](../-method/index.md)`, uri: `[`Uri`](../-uri/index.md)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Request`](./index.md)<br>`operator fun invoke(method: `[`Method`](../-method/index.md)`, uri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Request`](./index.md)<br>`operator fun invoke(method: `[`Method`](../-method/index.md)`, template: `[`UriTemplate`](../-uri-template/index.md)`, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1): `[`Request`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [alphabetiseHeaders](../alphabetise-headers.md) | `fun <T : `[`HttpMessage`](../-http-message/index.md)`> T.alphabetiseHeaders(): T` |
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Request`](./index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md)<br>`fun `[`Request`](./index.md)`.cookie(new: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Request`](./index.md)<br>`fun `[`Request`](./index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`?` |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Request`](./index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [form](../../org.http4k.core.body/form.md) | Returns the first form parameter with [name](../../org.http4k.core.body/form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).`fun `[`Request`](./index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?``fun `[`Request`](./index.md)`.form(): `[`Form`](../../org.http4k.core.body/-form.md)<br>`fun `[`Request`](./index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [formAsMap](../../org.http4k.core.body/form-as-map.md) | `fun `[`Request`](./index.md)`.formAsMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>>` |
| [fragmentParameter](../../org.http4k.security/fragment-parameter.md) | Retrieves the first fragment parameter value with this name.`fun `[`Request`](./index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>(Copy &amp;) Adds a query value with this name.`fun `[`Request`](./index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](./index.md) |
| [fragmentParameters](../../org.http4k.security/fragment-parameters.md) | Retrieves all fragment parameters with this name.`fun `[`Request`](./index.md)`.fragmentParameters(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [path](../../org.http4k.routing/path.md) | `fun `[`Request`](./index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Request`](./index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |
| [toCurl](../to-curl.md) | `fun `[`Request`](./index.md)`.toCurl(truncateBodyLength: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 256): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [parse](../parse.md) | `fun Request.Companion.parse(request: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](./index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [MemoryRequest](../-memory-request/index.md) | `data class MemoryRequest : `[`Request`](./index.md) |
| [RoutedRequest](../../org.http4k.routing/-routed-request/index.md) | `data class RoutedRequest : `[`Request`](./index.md) |
