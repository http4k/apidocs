[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryRequest](./index.md)

# MemoryRequest

`data class MemoryRequest : `[`Request`](../-request/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L214)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MemoryRequest(method: `[`Method`](../-method/index.md)`, uri: `[`Uri`](../-uri/index.md)`, headers: `[`Headers`](../-headers.md)` = listOf(), body: `[`Body`](../-body/index.md)` = EMPTY, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Body`](../-body/index.md) |
| [headers](headers.md) | `val headers: `[`Headers`](../-headers.md) |
| [method](method.md) | `val method: `[`Method`](../-method/index.md) |
| [uri](uri.md) | `val uri: `[`Uri`](../-uri/index.md) |
| [version](version.md) | `val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `fun body(body: `[`Body`](../-body/index.md)`): `[`MemoryRequest`](./index.md)<br>`fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md)<br>`fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) sets the body content. |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [header](header.md) | `fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) Adds a header value with this name. |
| [headers](headers.md) | `fun headers(headers: `[`Headers`](../-headers.md)`): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) Add all passed headers. |
| [method](method.md) | `fun method(method: `[`Method`](../-method/index.md)`): `[`Request`](../-request/index.md)<br>(Copy &amp;) sets the method. |
| [queries](queries.md) | `fun queries(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>`<br>Retrieves all query values with this name. |
| [query](query.md) | `fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) Adds a query value with this name.`fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Retrieves the first query value with this name. |
| [removeHeader](remove-header.md) | `fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) remove headers with this name. |
| [removeQuery](remove-query.md) | `fun removeQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) remove queries with this name. |
| [replaceHeader](replace-header.md) | `fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) Adds a header value with this name, replacing any previously set values. |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [uri](uri.md) | `fun uri(uri: `[`Uri`](../-uri/index.md)`): `[`MemoryRequest`](./index.md)<br>(Copy &amp;) sets the Uri. |

### Inherited Functions

| Name | Summary |
|---|---|
| [toMessage](../-request/to-message.md) | `open fun toMessage(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns a formatted wire representation of this message. |

### Extension Functions

| Name | Summary |
|---|---|
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Request`](../-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md)<br>`fun `[`Request`](../-request/index.md)`.cookie(new: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Request`](../-request/index.md)<br>`fun `[`Request`](../-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`?` |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Request`](../-request/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [form](../../org.http4k.core.body/form.md) | `fun `[`Request`](../-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Returns the first form parameter with [name](../../org.http4k.core.body/form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).`fun `[`Request`](../-request/index.md)`.form(): `[`Form`](../../org.http4k.core.body/-form.md)<br>`fun `[`Request`](../-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md) |
| [formAsMap](../../org.http4k.core.body/form-as-map.md) | `fun `[`Request`](../-request/index.md)`.formAsMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>>` |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [path](../../org.http4k.routing/path.md) | `fun `[`Request`](../-request/index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Request`](../-request/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../-request/index.md) |
| [toCurl](../to-curl.md) | `fun `[`Request`](../-request/index.md)`.toCurl(truncateBodyLength: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 256): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |
