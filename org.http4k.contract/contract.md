[http4k](../index.md) / [org.http4k.contract](index.md) / [contract](./contract.md)

# contract

`fun ~~contract~~(vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList() }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)`, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer }


`fun ~~contract~~(renderer: `[`ContractRenderer`](-contract-renderer/index.md)` = NoRenderer, descriptionPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", security: `[`Security`](../org.http4k.contract.security/-security/index.md)` = NoSecurity, vararg serverRoutes: `[`ContractRoute`](-contract-route/index.md)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)
**Deprecated:** Replaced with DSL version using contract { routes += serverRoutes.toList(); this.renderer = renderer; this.descriptionPath = descriptionPath; this.security = security }


`fun contract(fn: `[`ContractBuilder`](-contract-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`ContractRoutingHttpHandler`](-contract-routing-http-handler/index.md)