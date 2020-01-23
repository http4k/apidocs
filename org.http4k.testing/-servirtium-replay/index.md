[http4k](../../index.md) / [org.http4k.testing](../index.md) / [ServirtiumReplay](./index.md)

# ServirtiumReplay

`class ServirtiumReplay : `[`ParameterResolver`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterResolver.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-incubator/src/main/kotlin/org/http4k/testing/junitExtensions.kt#L47)

JUnit 5 extension for replaying HTTP traffic from disk in Servirtium format.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServirtiumReplay(root: `[`File`](https://docs.oracle.com/javase/9/docs/api/java/io/File.html)` = File("."))`<br>JUnit 5 extension for replaying HTTP traffic from disk in Servirtium format. |

### Functions

| Name | Summary |
|---|---|
| [resolveParameter](resolve-parameter.md) | `fun resolveParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |
| [supportsParameter](supports-parameter.md) | `fun supportsParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.5.2/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
