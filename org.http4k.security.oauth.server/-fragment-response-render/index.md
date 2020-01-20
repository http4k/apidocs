[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [FragmentResponseRender](./index.md)

# FragmentResponseRender

`class FragmentResponseRender : `[`ResponseRender`](../-response-render/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ResponseRender.kt#L45)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FragmentResponseRender(uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [addParameter](add-parameter.md) | `fun addParameter(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`ResponseRender`](../-response-render/index.md) |
| [complete](complete.md) | `fun complete(): `[`Response`](../../org.http4k.core/-response/index.md) |

### Inherited Functions

| Name | Summary |
|---|---|
| [withState](../-response-render/with-state.md) | `open fun withState(state: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`ResponseRender`](../-response-render/index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
