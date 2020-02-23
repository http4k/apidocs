[http4k](../../index.md) / [org.http4k.template](../index.md) / [Jade4jTemplates](./index.md)

# Jade4jTemplates

`class Jade4jTemplates : `[`Templates`](../-templates/index.md)

Jade4j templating support. Use the function in the constructor to configure the instance.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Jade4j templating support. Use the function in the constructor to configure the instance.`Jade4jTemplates(configure: JadeConfiguration = JadeConfiguration())` |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | Load and caches templates from a file path`fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [CachingClasspath](-caching-classpath.md) | Loads and caches templates from the compiled classpath`fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [HotReload](-hot-reload.md) | Hot-reloads (no-caching) templates from a file path`fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
