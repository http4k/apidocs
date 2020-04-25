[http4k](../../index.md) / [org.http4k.core](../index.md) / [MemoryResponse](./index.md)

# MemoryResponse

`data class MemoryResponse : `[`Response`](../-response/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MemoryResponse(status: `[`Status`](../-status/index.md)`, headers: `[`Headers`](../-headers.md)` = listOf(), body: `[`Body`](../-body/index.md)` = EMPTY, version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = HTTP_1_1)` |

### Properties

| Name | Summary |
|---|---|
| [body](body.md) | `val body: `[`Body`](../-body/index.md) |
| [headers](headers.md) | `val headers: `[`Headers`](../-headers.md) |
| [status](status.md) | `val status: `[`Status`](../-status/index.md) |
| [version](version.md) | `val version: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | (Copy &amp;) sets the body content.`fun body(body: `[`Body`](../-body/index.md)`): `[`MemoryResponse`](./index.md)<br>`fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryResponse`](./index.md)<br>`fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`MemoryResponse`](./index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [header](header.md) | (Copy &amp;) Adds a header value with this name.`fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryResponse`](./index.md) |
| [headers](headers.md) | (Copy &amp;) Add all passed headers.`fun headers(headers: `[`Headers`](../-headers.md)`): `[`MemoryResponse`](./index.md) |
| [removeHeader](remove-header.md) | (Copy &amp;) remove headers with this name.`fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MemoryResponse`](./index.md) |
| [replaceHeader](replace-header.md) | (Copy &amp;) Adds a header value with this name, replacing any previously set values.`fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`MemoryResponse`](./index.md) |
| [replaceHeaders](replace-headers.md) | Replace all headers with ones passed.`fun replaceHeaders(source: `[`Headers`](../-headers.md)`): `[`MemoryResponse`](./index.md) |
| [status](status.md) | `fun status(new: `[`Status`](../-status/index.md)`): `[`MemoryResponse`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [alphabetiseHeaders](../alphabetise-headers.md) | `fun <T : `[`HttpMessage`](../-http-message/index.md)`> T.alphabetiseHeaders(): T` |
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Response`](../-response/index.md)`.cookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](../-response/index.md) |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Response`](../-response/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [invalidateCookie](../../org.http4k.core.cookie/invalidate-cookie.md) | `fun `[`Response`](../-response/index.md)`.invalidateCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null): `[`Response`](../-response/index.md) |
| [maxAge](../max-age.md) | `fun `[`Response`](../-response/index.md)`.maxAge(duration: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`): `[`Response`](../-response/index.md) |
| [multipartIterator](../multipart-iterator.md) | `fun `[`HttpMessage`](../-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../-multipart-entity/index.md)`>` |
| [mustRevalidate](../must-revalidate.md) | `fun `[`Response`](../-response/index.md)`.mustRevalidate(): `[`Response`](../-response/index.md) |
| [noCache](../no-cache.md) | `fun `[`Response`](../-response/index.md)`.noCache(): `[`Response`](../-response/index.md) |
| [noStore](../no-store.md) | `fun `[`Response`](../-response/index.md)`.noStore(): `[`Response`](../-response/index.md) |
| [onlyIfCached](../only-if-cached.md) | `fun `[`Response`](../-response/index.md)`.onlyIfCached(): `[`Response`](../-response/index.md) |
| [private](../private.md) | `fun `[`Response`](../-response/index.md)`.private(): `[`Response`](../-response/index.md) |
| [public](../public.md) | `fun `[`Response`](../-response/index.md)`.public(): `[`Response`](../-response/index.md) |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Response`](../-response/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Response`](../-response/index.md) |
| [replaceCookie](../../org.http4k.core.cookie/replace-cookie.md) | `fun `[`Response`](../-response/index.md)`.replaceCookie(cookie: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Response`](../-response/index.md) |
| [staleIfError](../stale-if-error.md) | `fun `[`Response`](../-response/index.md)`.staleIfError(duration: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`): `[`Response`](../-response/index.md) |
| [staleWhileRevalidate](../stale-while-revalidate.md) | `fun `[`Response`](../-response/index.md)`.staleWhileRevalidate(duration: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`): `[`Response`](../-response/index.md) |
| [with](../with.md) | `fun <T : `[`HttpMessage`](../-http-message/index.md)`> T.with(vararg modifiers: (T) -> T): T` |
