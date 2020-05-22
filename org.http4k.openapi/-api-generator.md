[http4k](../index.md) / [org.http4k.openapi](index.md) / [ApiGenerator](./-api-generator.md)

# ApiGenerator

`interface ApiGenerator<T> : (T, `[`GenerationOptions`](-generation-options/index.md)`) -> `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FileSpec>`

### Inheritors

| Name | Summary |
|---|---|
| [ClientApiGenerator](../org.http4k.openapi.v2/-client-api-generator/index.md) | `object ClientApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi2Spec`](../org.http4k.openapi.v2/-open-api2-spec/index.md)`>` |
| [ClientApiGenerator](../org.http4k.openapi.v3.client/-client-api-generator/index.md) | `object ClientApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md)`>` |
| [ModelApiGenerator](../org.http4k.openapi.v2/-model-api-generator/index.md) | `object ModelApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi2Spec`](../org.http4k.openapi.v2/-open-api2-spec/index.md)`>` |
| [ModelApiGenerator](../org.http4k.openapi.v3.models/-model-api-generator/index.md) | `object ModelApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md)`>` |
| [ServerApiGenerator](../org.http4k.openapi.v2/-server-api-generator/index.md) | `object ServerApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi2Spec`](../org.http4k.openapi.v2/-open-api2-spec/index.md)`>` |
| [ServerApiGenerator](../org.http4k.openapi.v3.server/-server-api-generator/index.md) | `object ServerApiGenerator : `[`ApiGenerator`](./-api-generator.md)`<`[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md)`>` |
