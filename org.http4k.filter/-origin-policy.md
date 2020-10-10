[http4k](../index.md) / [org.http4k.filter](index.md) / [OriginPolicy](./-origin-policy.md)

# OriginPolicy

`interface OriginPolicy : (`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

For creating custom origin policy for allowing CORS

### Companion Object Extension Functions

| Name | Summary |
|---|---|
| [AllowAll](-allow-all.md) | Allows all origins for CORS`fun OriginPolicy.Companion.AllowAll(): `[`AllowAllOriginPolicy`](-allow-all-origin-policy/index.md) |
| [AnyOf](-any-of.md) | Allows a given list of origins for CORS`fun OriginPolicy.Companion.AnyOf(allowedOrigins: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`OriginPolicy`](./-origin-policy.md)<br>`fun OriginPolicy.Companion.AnyOf(vararg allowedOrigins: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`OriginPolicy`](./-origin-policy.md) |
| [Only](-only.md) | Allows a given single origin for CORS`fun OriginPolicy.Companion.Only(allowedOrigin: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`OriginPolicy`](./-origin-policy.md) |
| [Pattern](-pattern.md) | Allows origin(s) matching a Regex for CORS`fun OriginPolicy.Companion.Pattern(originRegex: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`OriginPolicy`](./-origin-policy.md) |

### Inheritors

| Name | Summary |
|---|---|
| [AllowAllOriginPolicy](-allow-all-origin-policy/index.md) | `object AllowAllOriginPolicy : `[`OriginPolicy`](./-origin-policy.md) |
