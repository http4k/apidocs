[http4k](../index.md) / [org.http4k.kotest](index.md) / [haveBody](./have-body.md)

# haveBody

`fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> haveBody(expected: Matcher<`[`Body`](../org.http4k.core/-body/index.md)`>): Matcher<T>`
`@JvmName("haveBodyNullableStringMatcher") fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> haveBody(expected: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<T>`
`fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> haveBody(expected: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): Matcher<T>`
`fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`> haveBody(expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): Matcher<T>`
`fun <T : `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`, B> haveBody(lens: `[`BodyLens`](../org.http4k.lens/-body-lens/index.md)`<B>, matcher: Matcher<B>): Matcher<T>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.haveBody(expected: NODE): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.haveBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun <NODE> `[`Json`](../org.http4k.format/-json/index.md)`<NODE>.haveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`