[http4k](../index.md) / [org.http4k.openapi.v2](./index.md)

## Package org.http4k.openapi.v2

### Types

| Name | Summary |
|---|---|
| [ClientApiGenerator](-client-api-generator/index.md) | `object ClientApiGenerator : `[`ApiGenerator`](../org.http4k.openapi/-api-generator.md)`<`[`OpenApi2Spec`](-open-api2-spec/index.md)`>` |
| [ModelApiGenerator](-model-api-generator/index.md) | `object ModelApiGenerator : `[`ApiGenerator`](../org.http4k.openapi/-api-generator.md)`<`[`OpenApi2Spec`](-open-api2-spec/index.md)`>` |
| [OpenApi2ParameterSpec](-open-api2-parameter-spec/index.md) | `sealed class OpenApi2ParameterSpec` |
| [OpenApi2PathSpec](-open-api2-path-spec/index.md) | `data class OpenApi2PathSpec` |
| [OpenApi2Spec](-open-api2-spec/index.md) | `data class OpenApi2Spec` |
| [ServerApiGenerator](-server-api-generator/index.md) | `object ServerApiGenerator : `[`ApiGenerator`](../org.http4k.openapi/-api-generator.md)`<`[`OpenApi2Spec`](-open-api2-spec/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [asV3](as-v3.md) | `fun `[`OpenApi2Spec`](-open-api2-spec/index.md)`.asV3(): `[`OpenApi3Spec`](../org.http4k.openapi.v3/-open-api3-spec/index.md) |
| [flatten](flatten.md) | For all parameters which are common (and represented in the paths as Refs), inline the content into the path so we can tell the type without looking up from the "global" list`fun `[`OpenApi2Spec`](-open-api2-spec/index.md)`.flatten(): `[`OpenApi2Spec`](-open-api2-spec/index.md) |
