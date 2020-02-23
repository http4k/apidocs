[http4k](../../index.md) / [org.http4k.junit](../index.md) / [ServirtiumRecording](./index.md)

# ServirtiumRecording

`class ServirtiumRecording : ParameterResolver, BeforeTestExecutionCallback, AfterTestExecutionCallback`

JUnit 5 extension for recording HTTP traffic to disk in Servirtium format.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | JUnit 5 extension for recording HTTP traffic to disk in Servirtium format.`ServirtiumRecording(baseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, httpHandler: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`, storageProvider: `[`StorageProvider`](../../org.http4k.servirtium/-storage-provider.md)`, options: `[`InteractionOptions`](../../org.http4k.servirtium/-interaction-options/index.md)` = Defaults)` |

### Functions

| Name | Summary |
|---|---|
| [afterTestExecution](after-test-execution.md) | `fun afterTestExecution(context: ExtensionContext): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [beforeTestExecution](before-test-execution.md) | `fun beforeTestExecution(context: ExtensionContext?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [resolveParameter](resolve-parameter.md) | `fun resolveParameter(pc: ParameterContext, ec: ExtensionContext): `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html) |
| [supportsParameter](supports-parameter.md) | `fun supportsParameter(pc: ParameterContext, ec: ExtensionContext): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
