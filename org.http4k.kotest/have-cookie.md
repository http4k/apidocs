[http4k](../index.md) / [org.http4k.kotest](index.md) / [haveCookie](./have-cookie.md)

# haveCookie

`fun haveCookie(expected: `[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`
`fun haveCookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, match: Matcher<`[`Cookie`](../org.http4k.core.cookie/-cookie/index.md)`>): Matcher<`[`Request`](../org.http4k.core/-request/index.md)`>`