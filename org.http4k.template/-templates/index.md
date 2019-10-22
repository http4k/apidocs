[http4k](../../index.md) / [org.http4k.template](../index.md) / [Templates](./index.md)

# Templates

`interface Templates` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/template/Templates.kt#L16)

Supported template implementations for templating engine implementations

### Functions

| Name | Summary |
|---|---|
| [Caching](-caching.md) | `abstract fun Caching(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md)<br>Load and caches templates from a file path |
| [CachingClasspath](-caching-classpath.md) | `abstract fun CachingClasspath(baseClasspathPackage: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = ""): `[`TemplateRenderer`](../-template-renderer.md)<br>Loads and caches templates from the compiled classpath |
| [HotReload](-hot-reload.md) | `abstract fun HotReload(baseTemplateDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "./"): `[`TemplateRenderer`](../-template-renderer.md)<br>Hot-reloads (no-caching) templates from a file path |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [DustTemplates](../-dust-templates/index.md) | `class DustTemplates : `[`Templates`](./index.md) |
| [FreemarkerTemplates](../-freemarker-templates/index.md) | `class FreemarkerTemplates : `[`Templates`](./index.md) |
| [HandlebarsTemplates](../-handlebars-templates/index.md) | `class HandlebarsTemplates : `[`Templates`](./index.md)<br>Handlebars templating support. Use the function in the constructor to configure the instance. |
| [Jade4jTemplates](../-jade4j-templates/index.md) | `class Jade4jTemplates : `[`Templates`](./index.md)<br>Jade4j templating support. Use the function in the constructor to configure the instance. |
| [PebbleTemplates](../-pebble-templates/index.md) | `class PebbleTemplates : `[`Templates`](./index.md) |
| [ThymeleafTemplates](../-thymeleaf-templates/index.md) | `class ThymeleafTemplates : `[`Templates`](./index.md) |
