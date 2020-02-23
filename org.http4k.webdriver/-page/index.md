[http4k](../../index.md) / [org.http4k.webdriver](../index.md) / [Page](./index.md)

# Page

`data class Page`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Page(status: `[`Status`](../../org.http4k.core/-status/index.md)`, navigate: `[`Navigate`](../-navigate.md)`, getURL: `[`GetURL`](../-get-u-r-l.md)`, handle: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, contents: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, previous: `[`Page`](./index.md)`? = null, next: `[`Page`](./index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [contents](contents.md) | `val contents: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [handle](handle.md) | `val handle: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html) |
| [next](next.md) | `val next: `[`Page`](./index.md)`?` |
| [previous](previous.md) | `val previous: `[`Page`](./index.md)`?` |
| [status](status.md) | `val status: `[`Status`](../../org.http4k.core/-status/index.md) |
| [title](title.md) | `val title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [url](url.md) | `val url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [findElement](find-element.md) | `fun findElement(by: By): WebElement?` |
| [findElements](find-elements.md) | `fun findElements(by: By): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<WebElement>` |
| [firstElement](first-element.md) | `fun firstElement(): `[`JSoupWebElement`](../-j-soup-web-element/index.md)`?` |
