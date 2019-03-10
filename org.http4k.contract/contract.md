[http4k](../index.md) / [org.http4k.contract](index.md) / [contract](./contract.md)

# contract

`fun contract(fn: `[`ContractBuilder`](-contract-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L9)
`fun ~~contract~~(vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L48)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList() }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L54)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L61)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)` = NoRenderer, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", security: `[`Security`](-security/index.md)` = NoSecurity, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-contract/src/main/kotlin/org/http4k/contract/extensions.kt#L69)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer; this.descriptionPath = descriptionPath; this.security = security }

