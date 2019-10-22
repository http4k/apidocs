[http4k](../../index.md) / [org.http4k.template](../index.md) / [Jade4jTemplates](./index.md)

# Jade4jTemplates

`class Jade4jTemplates : `[`Templates`](../-templates/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-jade4j/src/main/kotlin/org/http4k/template/Jade4jTemplates.kt#L16)

Jade4j templating support. Use the function in the constructor to configure the instance.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Jade4jTemplates(configure: JadeConfiguration = JadeConfiguration())`<br>Jade4j templating support. Use the function in the constructor to configure the instance. |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
