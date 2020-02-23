[http4k](../index.md) / [org.http4k.hamkrest](index.md) / [hasHeader](./has-header.md)

# hasHeader

`fun <T> hasHeader(lens: `[`HeaderLens`](../org.http4k.lens/-header-lens.md)`<T>, matcher: Matcher<T>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`@JvmName("hasBodyNullableString") fun hasHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, matcher: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`
`fun hasHeader(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`