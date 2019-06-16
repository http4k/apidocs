[http4k](../../index.md) / [org.http4k.routing](../index.md) / [RoutedRequest](./index.md)

# RoutedRequest

`data class RoutedRequest : `[`Request`](../../org.http4k.core/-request/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/routing.kt#L100)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RoutedRequest(delegate: `[`Request`](../../org.http4k.core/-request/index.md)`, xUriTemplate: `[`UriTemplate`](../../org.http4k.core/-uri-template/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [xUriTemplate](x-uri-template.md) | `val xUriTemplate: `[`UriTemplate`](../../org.http4k.core/-uri-template/index.md) |

### Functions

| Name | Summary |
|---|---|
| [body](body.md) | `fun body(body: `[`Body`](../../org.http4k.core/-body/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>`fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>`fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Request`](../../org.http4k.core/-request/index.md) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [header](header.md) | `fun header(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](../../org.http4k.core/-request/index.md) |
| [headers](headers.md) | `fun headers(headers: `[`Headers`](../../org.http4k.core/-headers.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [method](method.md) | `fun method(method: `[`Method`](../../org.http4k.core/-method/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [query](query.md) | `fun query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [removeHeader](remove-header.md) | `fun removeHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [replaceHeader](replace-header.md) | `fun replaceHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Request`](../../org.http4k.core/-request/index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [uri](uri.md) | `fun uri(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [cookie](../../org.http4k.core.cookie/cookie.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>`fun `[`Request`](../../org.http4k.core/-request/index.md)`.cookie(new: `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`): `[`Request`](../../org.http4k.core/-request/index.md)<br>`fun `[`Request`](../../org.http4k.core/-request/index.md)`.cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`?` |
| [cookies](../../org.http4k.core.cookie/cookies.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.cookies(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Cookie`](../../org.http4k.core.cookie/-cookie/index.md)`>` |
| [form](../../org.http4k.core.body/form.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Returns the first form parameter with [name](../../org.http4k.core.body/form.md#org.http4k.core.body$form(org.http4k.core.Request, kotlin.String)/name).`fun `[`Request`](../../org.http4k.core/-request/index.md)`.form(): `[`Form`](../../org.http4k.core.body/-form.md)<br>`fun `[`Request`](../../org.http4k.core/-request/index.md)`.form(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [formAsMap](../../org.http4k.core.body/form-as-map.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.formAsMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>>` |
| [multipartIterator](../../org.http4k.core/multipart-iterator.md) | `fun `[`HttpMessage`](../../org.http4k.core/-http-message/index.md)`.multipartIterator(): `[`Iterator`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)`<`[`MultipartEntity`](../../org.http4k.core/-multipart-entity/index.md)`>` |
| [path](../path.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.path(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [removeCookie](../../org.http4k.core.cookie/remove-cookie.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.removeCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](../../org.http4k.core/-request/index.md) |
| [toCurl](../../org.http4k.core/to-curl.md) | `fun `[`Request`](../../org.http4k.core/-request/index.md)`.toCurl(truncateBodyLength: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 256): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
