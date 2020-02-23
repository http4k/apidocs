[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](./index.md)

# ClientValidator

`interface ClientValidator`

Provides a consistent way to retrieve clients attempting to use an authorization code flow

### Functions

| Name | Summary |
|---|---|
| [validateClientId](validate-client-id.md) | <ul><li>check that client_id is a valid, registered app</li></ul>`abstract fun validateClientId(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validateCredentials](validate-credentials.md) | Validate that credentials provided by the client match its registration records`abstract fun validateCredentials(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validateRedirection](validate-redirection.md) | <ul><li>redirection URI is one of the allowed ones for that client</li></ul>`abstract fun validateRedirection(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, redirectionUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validateScopes](validate-scopes.md) | <ul><li>scopes are allowed for that client</li></ul>`abstract fun validateScopes(request: `[`Request`](../../org.http4k.core/-request/index.md)`, clientId: `[`ClientId`](../-client-id/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
