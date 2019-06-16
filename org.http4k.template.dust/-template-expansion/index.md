[http4k](../../index.md) / [org.http4k.template.dust](../index.md) / [TemplateExpansion](./index.md)

# TemplateExpansion

`interface TemplateExpansion` [(source)](https://github.com/http4k/http4k/blob/master/http4k-template-dust/src/main/kotlin/org/http4k/template/dust/Dust.kt#L16)

### Functions

| Name | Summary |
|---|---|
| [expandTemplate](expand-template.md) | `abstract fun expandTemplate(templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, params: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`, onMissingTemplate: (templateName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Nothing`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)` = ::missingTemplateIllegalArgument): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |

### Inheritors

| Name | Summary |
|---|---|
| [TemplateExpansionService](../-template-expansion-service.md) | `interface TemplateExpansionService : `[`AutoCloseable`](https://docs.oracle.com/javase/9/docs/api/java/lang/AutoCloseable.html)`, `[`TemplateExpansion`](./index.md) |
