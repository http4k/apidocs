[http4k](../../index.md) / [org.http4k.core](../index.md) / [RequestContext](./index.md)

# RequestContext

`class RequestContext`

### Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | `companion object Companion : `[`LensExtractor`](../../org.http4k.lens/-lens-extractor/index.md)`<`[`Request`](../-request/index.md)`, `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`>, `[`LensInjector`](../../org.http4k.lens/-lens-injector/index.md)`<`[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`, `[`Request`](../-request/index.md)`>` |

### Properties

| Name | Summary |
|---|---|
| [id](id.md) | `val id: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html) |

### Functions

| Name | Summary |
|---|---|
| [get](get.md) | `operator fun <T> get(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): T?` |
| [set](set.md) | `operator fun set(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | Lens operation to set the value into the target`fun <R : `[`Request`](../-request/index.md)`> invoke(value: `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html)`, target: R): R`<br>Lens operation to get the value from the target`fun invoke(target: `[`Request`](../-request/index.md)`): `[`UUID`](https://docs.oracle.com/javase/9/docs/api/java/util/UUID.html) |
