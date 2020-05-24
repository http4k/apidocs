[http4k](../../index.md) / [org.http4k.openapi.v3](../index.md) / [Path](./index.md)

# Path

`data class Path`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Path(urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, method: `[`Method`](../../org.http4k.core/-method/index.md)`, spec: `[`OpenApi3PathSpec`](../-open-api3-path-spec/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [method](method.md) | `val method: `[`Method`](../../org.http4k.core/-method/index.md) |
| [spec](spec.md) | `val spec: `[`OpenApi3PathSpec`](../-open-api3-path-spec/index.md) |
| [uniqueName](unique-name.md) | `val uniqueName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [urlPathPattern](url-path-pattern.md) | `val urlPathPattern: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [buildKDoc](build-k-doc.md) | `fun buildKDoc(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [requestSchemas](request-schemas.md) | `fun requestSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |
| [responseSchemas](response-schemas.md) | `fun responseSchemas(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`NamedSchema`](../../org.http4k.openapi/-named-schema/index.md)`>` |

### Extension Functions

| Name | Summary |
|---|---|
| [buildEndpoint](../../org.http4k.openapi.v3.server/build-endpoint.md) | `fun `[`Path`](./index.md)`.buildEndpoint(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FunSpec` |
| [buildWebForm](../../org.http4k.poet/build-web-form.md) | `fun `[`Path`](./index.md)`.buildWebForm(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
| [function](../../org.http4k.openapi.v3.client/function.md) | `fun `[`Path`](./index.md)`.function(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): FunSpec` |
| [parameterLensDeclarations](../../org.http4k.poet/parameter-lens-declarations.md) | `fun `[`Path`](./index.md)`.parameterLensDeclarations(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
| [requestLensDeclarations](../../org.http4k.poet/request-lens-declarations.md) | `fun `[`Path`](./index.md)`.requestLensDeclarations(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
| [responseLensDeclarations](../../org.http4k.poet/response-lens-declarations.md) | `fun `[`Path`](./index.md)`.responseLensDeclarations(modelPackageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
| [supportsFormContent](../../org.http4k.poet/supports-form-content.md) | `fun `[`Path`](./index.md)`.supportsFormContent(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [webFormLensDeclaration](../../org.http4k.poet/web-form-lens-declaration.md) | `fun `[`Path`](./index.md)`.webFormLensDeclaration(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<CodeBlock>` |
