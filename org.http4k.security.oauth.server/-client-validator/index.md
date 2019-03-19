[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidator](./index.md)

# ClientValidator

`interface ClientValidator` [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidator.kt#L8)

Provides a consistent way to retrieve clients attempting to use an authorization code flow

### Functions

| Name | Summary |
|---|---|
| [validateCredentials](validate-credentials.md) | `abstract fun validateCredentials(clientId: `[`ClientId`](../-client-id/index.md)`, clientSecret: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Validate that credentials provided by the client match its registration records |
| [validateRedirection](validate-redirection.md) | `abstract fun validateRedirection(clientId: `[`ClientId`](../-client-id/index.md)`, redirectionUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Client validation must include: |
