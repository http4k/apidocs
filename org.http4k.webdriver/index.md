[http4k](../index.md) / [org.http4k.webdriver](./index.md)

## Package org.http4k.webdriver

Code for testing http4k applications with the Webdriver library.

### Types

| Name | Summary |
|---|---|
| [By](-by/index.md) | Custom set of By implementations for testing http4k applications. As the backing store is JSoup we are limited to implementing selectors which are supported by that.`object By` |
| [FeatureNotImplementedYet](-feature-not-implemented-yet.md) | `object FeatureNotImplementedYet : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [GetURL](-get-u-r-l.md) | `typealias GetURL = () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [Http4KNavigation](-http4-k-navigation/index.md) | `interface Http4KNavigation : Navigation` |
| [Http4kWebDriver](-http4k-web-driver/index.md) | `class Http4kWebDriver : WebDriver` |
| [JSoupElementFinder](-j-soup-element-finder/index.md) | `class JSoupElementFinder : SearchContext` |
| [JSoupWebElement](-j-soup-web-element/index.md) | `data class JSoupWebElement : WebElement` |
| [Navigate](-navigate.md) | `typealias Navigate = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [Page](-page/index.md) | `data class Page` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | DSL-helper so we can use this webdriver in a lambda-with-receiver context`operator fun `[`Http4kWebDriver`](-http4k-web-driver/index.md)`.invoke(fn: `[`Http4kWebDriver`](-http4k-web-driver/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Http4kWebDriver`](-http4k-web-driver/index.md) |
