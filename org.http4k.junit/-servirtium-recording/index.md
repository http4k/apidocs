[http4k](../../index.md) / [org.http4k.junit](../index.md) / [ServirtiumRecording](./index.md)

# ServirtiumRecording

`class ServirtiumRecording : `[`ParameterResolver`](https://junit.org/junit5/docs/5.6.0/api/org/junit/jupiter/api/extension/ParameterResolver.html) [(source)](https://github.com/http4k/http4k/blob/master/http4k-testing-servirtium/src/main/kotlin/org/http4k/junit/junitExtensions.kt#L26)

JUnit 5 extension for recording HTTP traffic to disk in Servirtium format.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServirtiumRecording(baseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, storageLookup: `[`InteractionStorageLookup`](../../org.http4k.servirtium/-interaction-storage-lookup.md)` = Disk(), interactionOptions: `[`InteractionOptions`](../../org.http4k.servirtium/-interaction-options/index.md)` = Defaults)`<br>JUnit 5 extension for recording HTTP traffic to disk in Servirtium format. |

### Functions

| Name | Summary |
|---|---|
| [resolveParameter](resolve-parameter.md) | `fun resolveParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.6.0/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.6.0/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [supportsParameter](supports-parameter.md) | `fun supportsParameter(pc: `[`ParameterContext`](https://junit.org/junit5/docs/5.6.0/api/org/junit/jupiter/api/extension/ParameterContext.html)`, ec: `[`ExtensionContext`](https://junit.org/junit5/docs/5.6.0/api/org/junit/jupiter/api/extension/ExtensionContext.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
