[http4k](../../index.md) / [org.http4k.filter](../index.md) / [GenerateDataClasses](./index.md)

# GenerateDataClasses

`class GenerateDataClasses<out NODE> : `[`Filter`](../../org.http4k.core/-filter.md)

This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce
the number of class definitions by selecting the definition with the most fields (for cases where lists of items
have different fields).

### Types

| Name | Summary |
|---|---|
| [ArrayGen](-array-gen/index.md) | `data class ArrayGen : Gen` |
| [Gen](-gen/index.md) | `interface Gen : `[`Iterable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)`<Gen>` |
| [ObjectGen](-object-gen/index.md) | `data class ObjectGen : Gen` |
| [Primitives](-primitives/index.md) | `enum class Primitives : Gen` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | This Filter is used to generate Data class definitions from a Response containing JSON. The Filter will try and reduce the number of class definitions by selecting the definition with the most fields (for cases where lists of items have different fields).`GenerateDataClasses(json: `[`Json`](../../org.http4k.format/-json/index.md)`<NODE>, out: `[`PrintStream`](https://docs.oracle.com/javase/9/docs/api/java/io/PrintStream.html)` = System.out, idGenerator: () -> `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = { abs(Random.nextInt()) })` |

### Functions

| Name | Summary |
|---|---|
| [invoke](invoke.md) | `fun invoke(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [appliedWhen](../../org.http4k.chaos/applied-when.md) | `fun `[`Behaviour`](../../org.http4k.chaos/-behaviour.md)`.appliedWhen(trigger: `[`Trigger`](../../org.http4k.chaos/-trigger.md)`): `[`Stage`](../../org.http4k.chaos/-stage.md) |
| [then](../../org.http4k.core/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`Filter`](../../org.http4k.core/-filter.md)`): `[`Filter`](../../org.http4k.core/-filter.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(next: `[`HttpHandler`](../../org.http4k.core/-http-handler.md)`): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(routingHttpHandler: `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md)`): `[`RoutingHttpHandler`](../../org.http4k.routing/-routing-http-handler/index.md) |
| [then](../../org.http4k.serverless/then.md) | `fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)`): `[`AppLoader`](../../org.http4k.serverless/-app-loader.md)<br>`fun `[`Filter`](../../org.http4k.core/-filter.md)`.then(appLoader: `[`AppLoaderWithContexts`](../../org.http4k.serverless/-app-loader-with-contexts.md)`): <ERROR CLASS>` |
