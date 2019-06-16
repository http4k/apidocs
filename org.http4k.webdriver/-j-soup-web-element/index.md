[http4k](../../index.md) / [org.http4k.webdriver](../index.md) / [JSoupWebElement](./index.md)

# JSoupWebElement

`data class JSoupWebElement : `[`WebElement`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-webdriver/src/main/kotlin/org/http4k/webdriver/JSoupWebElement.kt#L20)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JSoupWebElement(navigate: `[`Navigate`](../-navigate.md)`, getURL: `[`GetURL`](../-get-u-r-l.md)`, element: `[`Element`](https://jsoup.org/apidocs/org/jsoup/nodes/Element.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [clear](clear.md) | `fun clear(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [click](click.md) | `fun click(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [equals](equals.md) | `fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [findElement](find-element.md) | `fun findElement(by: `[`By`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/By.html)`): `[`WebElement`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html)`?` |
| [findElements](find-elements.md) | `fun findElements(by: `[`By`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/By.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`WebElement`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/WebElement.html)`>` |
| [getAttribute](get-attribute.md) | `fun getAttribute(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getCssValue](get-css-value.md) | `fun getCssValue(propertyName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getLocation](get-location.md) | `fun getLocation(): `[`Point`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/Point.html) |
| [getRect](get-rect.md) | `fun getRect(): `[`Rectangle`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/Rectangle.html) |
| [getScreenshotAs](get-screenshot-as.md) | `fun <X> getScreenshotAs(target: `[`OutputType`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/OutputType.html)`<`[`X`](get-screenshot-as.md#X)`>?): `[`X`](get-screenshot-as.md#X) |
| [getSize](get-size.md) | `fun getSize(): `[`Dimension`](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/Dimension.html) |
| [getTagName](get-tag-name.md) | `fun getTagName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getText](get-text.md) | `fun getText(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [hashCode](hash-code.md) | `fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isDisplayed](is-displayed.md) | `fun isDisplayed(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEnabled](is-enabled.md) | `fun isEnabled(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isSelected](is-selected.md) | `fun isSelected(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sendKeys](send-keys.md) | `fun sendKeys(vararg keysToSend: `[`CharSequence`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-char-sequence/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [submit](submit.md) | `fun submit(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
