[http4k](../index.md) / [org.http4k.kotest](index.md) / [haveQuery](./have-query.md)

# haveQuery

`fun <T> haveQuery(lens: `[`QueryLens`](../org.http4k.lens/-query-lens.md)`<T>, matcher: Matcher<T>): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`@JvmName("haveQueryNullableStringMatcher") fun haveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, matcher: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveQuery(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`Uri`](../org.http4k.core/-uri/index.md)`>`