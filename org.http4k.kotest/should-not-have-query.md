[http4k](../index.md) / [org.http4k.kotest](index.md) / [shouldNotHaveQuery](./should-not-have-query.md)

# shouldNotHaveQuery

`fun <T> `[`Request`](../org.http4k.core/-request/index.md)`.shouldNotHaveQuery(lens: `[`QueryLens`](../org.http4k.lens/-query-lens.md)`<T>, matcher: Matcher<T>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`@JvmName("shouldNotHaveQueryNullableStringMatcher") fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldNotHaveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, matcher: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldNotHaveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldNotHaveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldNotHaveQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`infix fun `[`Uri`](../org.http4k.core/-uri/index.md)`.shouldNotHaveQuery(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)