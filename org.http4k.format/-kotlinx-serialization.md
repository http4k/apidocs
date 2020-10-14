[http4k](../index.md) / [org.http4k.format](index.md) / [KotlinxSerialization](./-kotlinx-serialization.md)

# KotlinxSerialization

`object KotlinxSerialization : `[`ConfigurableKotlinxSerialization`](-configurable-kotlinx-serialization/index.md)

To implement custom JSON configuration, create your own object singleton extending
ConfigurableKotlinxSerialization, passing in the JSON configuration block

### Extension Functions

| Name | Summary |
|---|---|
| [hasBody](../org.http4k.hamkrest/has-body.md) | `fun <NODE> `[`Json`](-json/index.md)`<NODE>.hasBody(expected: NODE): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<NODE>.hasBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<NODE>.hasBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>` |
| [haveBody](../org.http4k.kotest/have-body.md) | `fun <NODE> `[`Json`](-json/index.md)`<NODE>.haveBody(expected: NODE): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<NODE>.haveBody(expected: Matcher<NODE>): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>`<br>`fun <NODE> `[`Json`](-json/index.md)`<NODE>.haveBody(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): Matcher<`[`HttpMessage`](../org.http4k.core/-http-message/index.md)`>` |
