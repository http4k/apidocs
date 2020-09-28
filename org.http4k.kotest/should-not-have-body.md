[http4k](../index.md) / [org.http4k.kotest](index.md) / [shouldNotHaveBody](./should-not-have-body.md)

# shouldNotHaveBody

`infix fun `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`.shouldNotHaveBody(expected: Matcher<`[`Body`](../org.http4k.core/-body/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`@JvmName("shouldNotHaveBodyNullableStringMatcher") infix fun `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`.shouldNotHaveBody(expected: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`infix fun `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`.shouldNotHaveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`infix fun `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`.shouldNotHaveBody(expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun <T> `[`HttpMessage`](../org.http4k.core/-http-message/index.md)`.shouldNotHaveBody(lens: `[`BodyLens`](../org.http4k.lens/-body-lens/index.md)`<T>, matcher: Matcher<T>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)