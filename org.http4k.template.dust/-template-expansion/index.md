[http4k](../../index.md) / [org.http4k.template.dust](../index.md) / [TemplateExpansion](./index.md)

# TemplateExpansion

`interface TemplateExpansion`

### Functions

| Name | Summary |
|---|---|
| [expandTemplate](expand-template.md) | `abstract fun expandTemplate(templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, params: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, onMissingTemplate: (templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)` = ::missingTemplateIllegalArgument): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [TemplateExpansionService](../-template-expansion-service.md) | `interface TemplateExpansionService : `[`AutoCloseable`](https://docs.oracle.com/javase/9/docs/api/java/lang/AutoCloseable.html)`, `[`TemplateExpansion`](./index.md) |
