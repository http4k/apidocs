[http4k](../index.md) / [org.http4k.contract.security](./index.md)

## Package org.http4k.contract.security

### Types

| Name | Summary |
|---|---|
| [ApiKeySecurity](-api-key-security/index.md) | `class ApiKeySecurity<out T> : `[`Security`](-security/index.md)<br>Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request. |
| [BasicAuthSecurity](-basic-auth-security/index.md) | `class BasicAuthSecurity : `[`Security`](-security/index.md)<br>Checks the presence of basic auth credentials. Filter returns 401 if auth fails. |
| [BearerAuthSecurity](-bearer-auth-security/index.md) | `class BearerAuthSecurity : `[`Security`](-security/index.md)<br>Checks the presence of bearer auth credentials. Filter returns 401 if auth fails. |
| [NoSecurity](-no-security/index.md) | `object NoSecurity : `[`Security`](-security/index.md)<br>Default NoOp security filter. Filter allows all traffic through. |
| [OAuthScope](-o-auth-scope/index.md) | `data class OAuthScope` |
| [OAuthSecurity](-o-auth-security/index.md) | `data class OAuthSecurity : `[`Security`](-security/index.md) |
| [Security](-security/index.md) | `interface Security`<br>Endpoint security. Provides filter to be applied to endpoints for all requests. |
