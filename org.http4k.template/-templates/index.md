[http4k](../../index.md) / [org.http4k.template](../index.md) / [Templates](./index.md)

# Templates

`interface Templates`

Supported template implementations for templating engine implementations

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | Load and caches templates from a file path`abstract fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md) |
| [CachingClasspath](-caching-classpath.md) | Loads and caches templates from the compiled classpath`abstract fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ""): `[`TemplateRenderer`](../-template-renderer.md) |
| [HotReload](-hot-reload.md) | Hot-reloads (no-caching) templates from a file path`abstract fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md) |

### Inheritors

| Name | Summary |
|---|---|
| [DustTemplates](../-dust-templates/index.md) | `class DustTemplates : `[`Templates`](./index.md) |
| [FreemarkerTemplates](../-freemarker-templates/index.md) | `class FreemarkerTemplates : `[`Templates`](./index.md) |
| [HandlebarsTemplates](../-handlebars-templates/index.md) | Handlebars templating support. Use the function in the constructor to configure the instance.`class HandlebarsTemplates : `[`Templates`](./index.md) |
| [Jade4jTemplates](../-jade4j-templates/index.md) | Jade4j templating support. Use the function in the constructor to configure the instance.`class Jade4jTemplates : `[`Templates`](./index.md) |
| [PebbleTemplates](../-pebble-templates/index.md) | `class PebbleTemplates : `[`Templates`](./index.md) |
| [ThymeleafTemplates](../-thymeleaf-templates/index.md) | `class ThymeleafTemplates : `[`Templates`](./index.md) |
