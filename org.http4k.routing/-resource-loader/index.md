[http4k](../../index.md) / [org.http4k.routing](../index.md) / [ResourceLoader](./index.md)

# ResourceLoader

`interface ResourceLoader`

Looks up contents of a resource path.

WARNING: A ResourceLoader serves ANY resource it finds within it's structure. This means that you should be
VERY careful to limit what resources it has access to.

### Functions

| Name | Summary |
|---|---|
| [load](load.md) | `abstract fun load(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html)`?` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [Classpath](-classpath.md) | `fun Classpath(basePackagePath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "/", muteWarning: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`ResourceLoader`](./index.md) |
| [Directory](-directory.md) | `fun Directory(baseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "."): `[`ResourceLoader`](./index.md) |
