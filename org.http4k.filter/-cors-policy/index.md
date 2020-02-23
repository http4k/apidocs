[http4k](../../index.md) / [org.http4k.filter](../index.md) / [CorsPolicy](./index.md)

# CorsPolicy

`data class CorsPolicy`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CorsPolicy(origins: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, headers: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, methods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Method`](../../org.http4k.core/-method/index.md)`>, credentials: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false)` |

### Properties

| Name | Summary |
|---|---|
| [credentials](credentials.md) | `val credentials: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [headers](headers.md) | `val headers: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [methods](methods.md) | `val methods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Method`](../../org.http4k.core/-method/index.md)`>` |
| [origins](origins.md) | `val origins: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Companion Object Properties

| Name | Summary |
|---|---|
| [UnsafeGlobalPermissive](-unsafe-global-permissive.md) | `val UnsafeGlobalPermissive: `[`CorsPolicy`](./index.md) |
