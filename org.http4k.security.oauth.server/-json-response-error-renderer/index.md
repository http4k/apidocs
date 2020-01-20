[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [JsonResponseErrorRenderer](./index.md)

# JsonResponseErrorRenderer

`class JsonResponseErrorRenderer` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/JsonResponseErrorRenderer.kt#L12)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JsonResponseErrorRenderer(json: `[`AutoMarshallingJson`](../../org.http4k.format/-auto-marshalling-json/index.md)`, documentationUri: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null)` |

### Functions

| Name | Summary |
|---|---|
| [response](response.md) | `fun response(error: `[`OAuthError`](../-o-auth-error/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
