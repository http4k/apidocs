[http4k](../../index.md) / [org.http4k.filter.cookie](../index.md) / [CookieStorage](./index.md)

# CookieStorage

`interface CookieStorage`

### Functions

| Name | Summary |
|---|---|
| [remove](remove.md) | `abstract fun remove(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [retrieve](retrieve.md) | `abstract fun retrieve(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LocalCookie`](../-local-cookie/index.md)`>` |
| [store](store.md) | `abstract fun store(cookies: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LocalCookie`](../-local-cookie/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [BasicCookieStorage](../-basic-cookie-storage/index.md) | `class BasicCookieStorage : `[`CookieStorage`](./index.md) |
