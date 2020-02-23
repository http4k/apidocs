[http4k](../../index.md) / [org.http4k.filter](../index.md) / [CacheControlHeaderPart](./index.md)

# CacheControlHeaderPart

`open class CacheControlHeaderPart`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CacheControlHeaderPart(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `open val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [value](value.md) | `val value: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html) |

### Functions

| Name | Summary |
|---|---|
| [replaceIn](replace-in.md) | `fun replaceIn(header: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [toHeaderValue](to-header-value.md) | `fun toHeaderValue(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [MaxAgeTtl](../-max-age-ttl/index.md) | `data class MaxAgeTtl : `[`CacheControlHeaderPart`](./index.md) |
| [StaleIfErrorTtl](../-stale-if-error-ttl/index.md) | `data class StaleIfErrorTtl : `[`CacheControlHeaderPart`](./index.md) |
| [StaleWhenRevalidateTtl](../-stale-when-revalidate-ttl/index.md) | `data class StaleWhenRevalidateTtl : `[`CacheControlHeaderPart`](./index.md) |
