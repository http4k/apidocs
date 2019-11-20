[http4k](../../index.md) / [org.http4k.core](../index.md) / [Request](index.md) / [body](./body.md)

# body

`abstract fun body(body: `[`Body`](../-body/index.md)`): `[`Request`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L198)

Overrides [HttpMessage.body](../-http-message/body.md)


`abstract fun body(body: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Request`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L200)

Overrides [HttpMessage.body](../-http-message/body.md)


`abstract fun body(body: `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html)`, length: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?): `[`Request`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/http.kt#L202)

Overrides [HttpMessage.body](../-http-message/body.md)

(Copy &amp;) sets the body content.

