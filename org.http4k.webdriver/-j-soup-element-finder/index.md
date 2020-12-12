[http4k](../../index.md) / [org.http4k.webdriver](../index.md) / [JSoupElementFinder](./index.md)

# JSoupElementFinder

`class JSoupElementFinder : FindsByCssSelector, FindsByTagName, FindsById, FindsByClassName, SearchContext`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JSoupElementFinder(navigate: `[`Navigate`](../-navigate.md)`, getURL: `[`GetURL`](../-get-u-r-l.md)`, element: Element)` |

### Functions

| Name | Summary |
|---|---|
| [findElement](find-element.md) | `fun findElement(by: By): WebElement?` |
| [findElementByClassName](find-element-by-class-name.md) | `fun findElementByClassName(className: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): WebElement?` |
| [findElementByCssSelector](find-element-by-css-selector.md) | `fun findElementByCssSelector(selector: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): WebElement?` |
| [findElementById](find-element-by-id.md) | `fun findElementById(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): WebElement?` |
| [findElementByTagName](find-element-by-tag-name.md) | `fun findElementByTagName(tagName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): WebElement?` |
| [findElements](find-elements.md) | `fun findElements(by: By): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [findElementsByClassName](find-elements-by-class-name.md) | `fun findElementsByClassName(className: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [findElementsByCssSelector](find-elements-by-css-selector.md) | `fun findElementsByCssSelector(selector: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [findElementsById](find-elements-by-id.md) | `fun findElementsById(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [findElementsByTagName](find-elements-by-tag-name.md) | `fun findElementsByTagName(tagName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
