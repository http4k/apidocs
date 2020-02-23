[http4k](../../index.md) / [org.http4k.template](../index.md) / [FreemarkerTemplates](./index.md)

# FreemarkerTemplates

`class FreemarkerTemplates : `[`Templates`](../-templates/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FreemarkerTemplates(configure: (Configuration) -> Configuration = { it }, classLoader: `[`ClassLoader`](https://docs.oracle.com/javase/9/docs/api/java/lang/ClassLoader.html)` = ClassLoader.getSystemClassLoader())` |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | Load and caches templates from a file path`fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [CachingClasspath](-caching-classpath.md) | Loads and caches templates from the compiled classpath`fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [HotReload](-hot-reload.md) | Hot-reloads (no-caching) templates from a file path`fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
