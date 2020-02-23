[http4k](../../../index.md) / [org.http4k.cloudnative.env](../../index.md) / [EnvironmentKey](../index.md) / [k8s](./index.md)

# k8s

`object k8s`

### Properties

| Name | Summary |
|---|---|
| [HEALTH_PORT](-h-e-a-l-t-h_-p-o-r-t.md) | `val HEALTH_PORT: `[`BiDiLens`](../../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [SERVICE_PORT](-s-e-r-v-i-c-e_-p-o-r-t.md) | `val SERVICE_PORT: `[`BiDiLens`](../../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `operator fun <T> invoke(fn: k8s.() -> T): T` |
| [serviceUriFor](service-uri-for.md) | `fun serviceUriFor(serviceName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isHttps: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`BiDiLens`](../../../org.http4k.lens/-bi-di-lens/index.md)`<`[`Environment`](../../-environment/index.md)`, `[`Uri`](../../../org.http4k.core/-uri/index.md)`>` |
