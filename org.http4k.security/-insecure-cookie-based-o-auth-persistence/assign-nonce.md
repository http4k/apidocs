[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [assignNonce](./assign-nonce.md)

# assignNonce

`fun assignNonce(redirect: `[`Response`](../../org.http4k.core/-response/index.md)`, nonce: `[`Nonce`](../../org.http4k.security.openid/-nonce/index.md)`): `[`Response`](../../org.http4k.core/-response/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/InsecureCookieBasedOAuthPersistence.kt#L41)

Overrides [OAuthPersistence.assignNonce](../-o-auth-persistence/assign-nonce.md)

Assign a nonce to this OIDC auth redirection (to the end-service) response. Opportunity here to modify the
response returned to the user when the redirection happens.

