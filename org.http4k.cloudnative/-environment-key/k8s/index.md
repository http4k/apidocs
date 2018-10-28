[http4k](../../../index.md) / [org.http4k.cloudnative](../../index.md) / [EnvironmentKey](../index.md) / [k8s](./index.md)

# k8s

`object k8s` [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/Environment.kt#L36)

### Properties

| Name | Summary |
|---|---|
| [HEALTH_PORT](-h-e-a-l-t-h_-p-o-r-t.md) | `val HEALTH_PORT: `[`BiDiLens`](../../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [SERVICE_PORT](-s-e-r-v-i-c-e_-p-o-r-t.md) | `val SERVICE_PORT: `[`BiDiLens`](../../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [serviceUriFor](service-uri-for.md) | `fun serviceUriFor(serviceName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, https: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`Lens`](../../../org.http4k.lens/-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Uri`](../../../org.http4k.core/-uri/index.md)`>` |
