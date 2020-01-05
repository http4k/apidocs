[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ServirtiumRecording](./index.md)

# ServirtiumRecording

`class ServirtiumRecording : `[`BeforeTestExecutionCallback`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/BeforeTestExecutionCallback.html)`, `[`ParameterResolver`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterResolver.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/testing/ServirtiumRecording.kt#L15)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServirtiumRecording(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, original: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."))` |

### Functions

| Name | Summary |
|---|---|
| [beforeTestExecution](before-test-execution.md) | `fun beforeTestExecution(ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](resolve-parameter.md) | `fun resolveParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?` |
| [supportsParameter](supports-parameter.md) | `fun supportsParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
