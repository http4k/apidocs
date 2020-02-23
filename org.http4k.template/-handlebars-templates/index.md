[http4k](../../index.md) / [org.http4k.template](../index.md) / [HandlebarsTemplates](./index.md)

# HandlebarsTemplates

`class HandlebarsTemplates : `[`Templates`](../-templates/index.md)

Handlebars templating support. Use the function in the constructor to configure the instance.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Handlebars templating support. Use the function in the constructor to configure the instance.`HandlebarsTemplates(configure: (Handlebars) -> Handlebars = { it })` |

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | Load and caches templates from a file path`fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [CachingClasspath](-caching-classpath.md) | Loads and caches templates from the compiled classpath`fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
| [HotReload](-hot-reload.md) | Hot-reloads (no-caching) templates from a file path`fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md)<br>`fun HotReload(firstBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, secondBaseDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg rest: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TemplateRenderer`](../-template-renderer.md) |
