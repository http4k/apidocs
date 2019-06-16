[http4k](../../index.md) / [org.http4k.routing](../index.md) / [ResourceLoader](./index.md)

# ResourceLoader

`interface ResourceLoader` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/routing/ResourceLoader.kt#L6)

### Functions

| Name | Summary |
|---|---|
| [load](load.md) | `abstract fun load(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html)`?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Classpath](-classpath.md) | `fun Classpath(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/"): `[`ResourceLoader`](./index.md) |
| [Directory](-directory.md) | `fun Directory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`ResourceLoader`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
