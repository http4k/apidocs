[http4k](../../index.md) / [org.http4k.template.dust](../index.md) / [Dust](./index.md)

# Dust

`class Dust`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Dust(cacheTemplates: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, precachePoolSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, dustPluginScripts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`URL`](https://docs.oracle.com/javase/9/docs/api/java/net/URL.html)`>, loader: `[`TemplateLoader`](../-template-loader.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [openTemplates](open-templates.md) | `fun openTemplates(): `[`TemplateExpansionService`](../-template-expansion-service.md) |
| [withTemplates](with-templates.md) | `fun <T> withTemplates(block: (`[`TemplateExpansion`](../-template-expansion/index.md)`) -> T): T` |
