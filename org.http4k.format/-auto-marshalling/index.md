[http4k](../../index.md) / [org.http4k.format](../index.md) / [AutoMarshalling](./index.md)

# AutoMarshalling

`abstract class AutoMarshalling`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AutoMarshalling()` |

### Functions

| Name | Summary |
|---|---|
| [asA](as-a.md) | `abstract fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> asA(input: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): T`<br>`fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.asA(target: `[`KClass`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)`<T>): T` |
| [asInputStream](as-input-stream.md) | `fun asInputStream(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`InputStream`](https://docs.oracle.com/javase/9/docs/api/java/io/InputStream.html) |
| [asString](as-string.md) | `abstract fun asString(input: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AutoMarshallingJson](../-auto-marshalling-json/index.md) | `abstract class AutoMarshallingJson : `[`AutoMarshalling`](./index.md) |
| [AutoMarshallingXml](../-auto-marshalling-xml/index.md) | `abstract class AutoMarshallingXml : `[`AutoMarshalling`](./index.md) |
