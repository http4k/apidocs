[http4k](../index.md) / [org.http4k.template.dust](index.md) / [TemplateExpansionService](./-template-expansion-service.md)

# TemplateExpansionService

`interface TemplateExpansionService : `[`AutoCloseable`](https://docs.oracle.com/javase/6/docs/api/java/lang/AutoCloseable.html)`, `[`TemplateExpansion`](-template-expansion/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-dust/src/main/kotlin/org/http4k/template/dust/Dust.kt#L24)

### Inherited Functions

| Name | Summary |
|---|---|
| [expandTemplate](-template-expansion/expand-template.md) | `abstract fun expandTemplate(templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, params: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, onMissingTemplate: (templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)` = ::missingTemplateIllegalArgument): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../org.http4k.core/with.md) | `fun <T> `[`T`](../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../org.http4k.core/with.md#T)`) -> `[`T`](../org.http4k.core/with.md#T)`): `[`T`](../org.http4k.core/with.md#T) |
