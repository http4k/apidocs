[http4k](../index.md) / [org.http4k.hamkrest](index.md) / [hasBody](./has-body.md)

# hasBody

`fun hasBody(expected: Matcher<`[`Body`](../org.http4k.core/-body/index.md)`>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`@JvmName("hasBodyNullableString") fun hasBody(expected: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasBody(expected: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasBody(expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <T> hasBody(lens: `[`BodyLens`](../org.http4k.lens/-body-lens/index.md)`<T>, matcher: Matcher<T>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.hasBody(expected: NODE): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.hasBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`