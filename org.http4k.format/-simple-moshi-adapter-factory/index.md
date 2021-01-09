[http4k](../../index.md) / [org.http4k.format](../index.md) / [SimpleMoshiAdapterFactory](./index.md)

# SimpleMoshiAdapterFactory

`open class SimpleMoshiAdapterFactory : Factory`

Convenience class to create Moshi Adapter Factory

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Convenience class to create Moshi Adapter Factory`SimpleMoshiAdapterFactory(vararg typesToAdapters: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, (Moshi) -> JsonAdapter<*>>)` |

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `open fun create(type: `[`Type`](https://docs.oracle.com/javase/9/docs/api/java/lang/reflect/Type.html)`, annotations: `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`Annotation`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-annotation/index.html)`>, moshi: Moshi): JsonAdapter<*>?` |
