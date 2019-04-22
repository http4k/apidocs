[http4k](../../index.md) / [org.http4k.security](../index.md) / [OAuthRedirectionFilter](./index.md)

# OAuthRedirectionFilter

`class OAuthRedirectionFilter : `[`Filter`](../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/OAuthRedirectionFilter.kt#L7)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OAuthRedirectionFilter(providerConfig: `[`OAuthProviderConfig`](../-o-auth-provider-config/index.md)`, callbackUri: `[`Uri`](../../org.http4k.core/-uri/index.md)`, scopes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, generateCrsf: `[`CsrfGenerator`](../-csrf-generator.md)` = CrossSiteRequestForgeryToken.SECURE_CSRF, modifyState: (`[`Uri`](../../org.http4k.core/-uri/index.md)`) -> `[`Uri`](../../org.http4k.core/-uri/index.md)`, oAuthPersistence: `[`OAuthPersistence`](../-o-auth-persistence/index.md)`, responseType: `[`ResponseType`](../-response-type/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [with](../../org.http4k.core/with.md) | `fun <T> `[`T`](../../org.http4k.core/with.md#T)`.with(vararg modifiers: (`[`T`](../../org.http4k.core/with.md#T)`) -> `[`T`](../../org.http4k.core/with.md#T)`): `[`T`](../../org.http4k.core/with.md#T) |
