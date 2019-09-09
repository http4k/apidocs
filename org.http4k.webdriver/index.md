[http4k](../index.md) / [org.http4k.webdriver](./index.md)

## Package org.http4k.webdriver

Code for testing http4k applications with the Webdriver library.

### Types

| Name | Summary |
|---|---|
| [FeatureNotImplementedYet](-feature-not-implemented-yet.md) | `object FeatureNotImplementedYet : `[`Exception`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) |
| [Http4KNavigation](-http4-k-navigation/index.md) | `interface Http4KNavigation : `[`Navigation`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebDriver/Navigation.html) |
| [Http4kWebDriver](-http4k-web-driver/index.md) | `class Http4kWebDriver : `[`WebDriver`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebDriver.html) |
| [JSoupWebElement](-j-soup-web-element/index.md) | `data class JSoupWebElement : `[`WebElement`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html) |
| [Page](-page/index.md) | `data class Page` |

### Type Aliases

| Name | Summary |
|---|---|
| [GetURL](-get-u-r-l.md) | `typealias GetURL = () -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [Navigate](-navigate.md) | `typealias Navigate = (`[`Request`](../org.http4k.core/-request/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun `[`Http4kWebDriver`](-http4k-web-driver/index.md)`.invoke(fn: `[`Http4kWebDriver`](-http4k-web-driver/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Http4kWebDriver`](-http4k-web-driver/index.md)<br>DSL-helper so we can use this webdriver in a lambda-with-receiver context |
