[http4k](../index.md) / [org.http4k.kotest](index.md) / [shouldHaveCookie](./should-have-cookie.md)

# shouldHaveCookie

`infix fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldHaveCookie(expected: `[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldHaveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldHaveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)
`fun `[`Request`](../org.http4k.core/-request/index.md)`.shouldHaveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, match: Matcher<`[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)