[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryRequest](./index.md)

# MemoryRequest

`data class MemoryRequest : `[`Request`](../-request/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MemoryRequest(method: `[`Method`](../-method/index.md)`, uri: `[`Uri`](../-uri/index.md)`, headers: `[`Headers`](../-headers.md)` = listOf(), body: `[`Body`](../-body/index.md)` = EMPTY, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1, sourceAddress: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, sourcePort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Body`](../-body/index.md) |
| [headers](headers.md) | `val headers: `[`Headers`](../-headers.md) |
| [method](method.md) | `val method: `[`Method`](../-method/index.md) |
| [sourceAddress](source-address.md) | `val sourceAddress: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [sourcePort](source-port.md) | `val sourcePort: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [uri](uri.md) | `val uri: `[`Uri`](../-uri/index.md) |
| [version](version.md) | `val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | (Copy &amp;) sets the body content.`fun body(body: `[`Body`](../-body/index.md)`): `[`MemoryRequest`](./index.md)<br>`fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md)<br>`fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`MemoryRequest`](./index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [header](header.md) | (Copy &amp;) Adds a header value with this name.`fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md) |
| [headers](headers.md) | (Copy &amp;) Add all passed headers.`fun headers(headers: `[`Headers`](../-headers.md)`): `[`MemoryRequest`](./index.md) |
| [method](method.md) | (Copy &amp;) sets the method.`fun method(method: `[`Method`](../-method/index.md)`): `[`Request`](../-request/index.md) |
| [queries](queries.md) | Retrieves all query values with this name.`fun queries(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [query](query.md) | (Copy &amp;) Adds a query value with this name.`fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md)<br>Retrieves the first query value with this name.`fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeHeader](remove-header.md) | (Copy &amp;) remove headers with this name.`fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md) |
| [removeQuery](remove-query.md) | (Copy &amp;) remove queries with this name.`fun removeQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md) |
| [replaceHeader](replace-header.md) | (Copy &amp;) Adds a header value with this name, replacing any previously set values.`fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md) |
| [replaceHeaders](replace-headers.md) | Replace all headers with ones passed.`fun replaceHeaders(source: `[`Headers`](../-headers.md)`): `[`MemoryRequest`](./index.md) |
| [sourceAddress](source-address.md) | (Copy &amp;) sets source address.`fun sourceAddress(address: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md) |
| [sourcePort](source-port.md) | (Copy &amp;) sets source port.`fun sourcePort(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`MemoryRequest`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [uri](uri.md) | (Copy &amp;) sets the Uri.`fun uri(uri: `[`Uri`](../-uri/index.md)`): `[`MemoryRequest`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [alphabetiseHeaders](../alphabetise-headers.md) | `fun <T : `[`HttpMessage`](../-http-message/index.md)`> T.alphabetiseHeaders(): T` |
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Request`](../-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md)<br>`fun `[`Request`](../-request/index.md)`.cookie(new: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Request`](../-request/index.md)<br>`fun `[`Request`](../-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`?` |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Request`](../-request/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [form](../../org.http4k.core.body/form.md) | Returns the first form parameter with [name](../../org.http4k.core.body/form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).`fun `[`Request`](../-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?``fun `[`Request`](../-request/index.md)`.form(): `[`Form`](../../org.http4k.core.body/-form.md)<br>`fun `[`Request`](../-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md) |
| [formAsMap](../../org.http4k.core.body/form-as-map.md) | `fun `[`Request`](../-request/index.md)`.formAsMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>>` |
| [fragmentParameter](../../org.http4k.security/fragment-parameter.md) | Retrieves the first fragment parameter value with this name.`fun `[`Request`](../-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>(Copy &amp;) Adds a query value with this name.`fun `[`Request`](../-request/index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](../-request/index.md) |
| [fragmentParameters](../../org.http4k.security/fragment-parameters.md) | Retrieves all fragment parameters with this name.`fun `[`Request`](../-request/index.md)`.fragmentParameters(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>` |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [path](../../org.http4k.routing/path.md) | `fun `[`Request`](../-request/index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Request`](../-request/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md) |
| [toCurl](../to-curl.md) | `fun `[`Request`](../-request/index.md)`.toCurl(truncateBodyLength: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 256): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [with](../with.md) | `fun <T : `[`HttpMessage`](../-http-message/index.md)`> T.with(vararg modifiers: (T) -> T): T` |
