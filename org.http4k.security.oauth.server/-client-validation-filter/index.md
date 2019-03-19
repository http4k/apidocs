[http4k](../../index.md) / [org.http4k.security.oauth.server](../index.md) / [ClientValidationFilter](./index.md)

# ClientValidationFilter

`class ClientValidationFilter : `[`Filter`](../../org.http4k.core/-filter/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-security-oauth/src/main/kotlin/org/http4k/security/oauth/server/ClientValidationFilter.kt#L10)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClientValidationFilter(clientValidator: `[`ClientValidator`](../-client-validator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter/index.md)`): `[`Filter`](../../org.http4k.core/-filter/index.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter/index.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
