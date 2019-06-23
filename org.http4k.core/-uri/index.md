[http4k](../../index.md) / [org.http4k.core](../index.md) / [Uri](./index.md)

# Uri

`data class Uri : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`Uri`](./index.md)`>` [(source)](https://github.com/http4k/http4k/blob/master/http4k-core/src/main/kotlin/org/http4k/core/Uri.kt#L8)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Uri(scheme: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, userInfo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, host: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?, path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, fragment: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [authority](authority.md) | `val authority: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [fragment](fragment.md) | `val fragment: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [host](host.md) | `val host: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [path](path.md) | `val path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [port](port.md) | `val port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?` |
| [query](query.md) | `val query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [scheme](scheme.md) | `val scheme: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [userInfo](user-info.md) | `val userInfo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [authority](authority.md) | `fun authority(authority: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [compareTo](compare-to.md) | `fun compareTo(other: `[`Uri`](./index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fragment](fragment.md) | `fun fragment(fragment: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [host](host.md) | `fun host(host: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [path](path.md) | `fun path(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [port](port.md) | `fun port(port: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?): `[`Uri`](./index.md) |
| [query](query.md) | `fun query(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [scheme](scheme.md) | `fun scheme(scheme: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [userInfo](user-info.md) | `fun userInfo(userInfo: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [of](of.md) | `fun of(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |

### Extension Functions

| Name | Summary |
|---|---|
| [authority](../authority.md) | `fun `[`Uri`](./index.md)`.authority(authority: `[`Authority`](../../org.http4k.cloudnative.env/-authority/index.md)`): `[`Uri`](./index.md)<br>`fun `[`Uri`](./index.md)`.authority(): `[`Authority`](../../org.http4k.cloudnative.env/-authority/index.md) |
| [extend](../extend.md) | `fun `[`Uri`](./index.md)`.extend(uri: `[`Uri`](./index.md)`): `[`Uri`](./index.md) |
| [host](../host.md) | `fun `[`Uri`](./index.md)`.host(): `[`Host`](../../org.http4k.cloudnative.env/-host/index.md)<br>`fun `[`Uri`](./index.md)`.host(host: `[`Host`](../../org.http4k.cloudnative.env/-host/index.md)`): `[`Uri`](./index.md) |
| [port](../port.md) | `fun `[`Uri`](./index.md)`.port(port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`?): `[`Uri`](./index.md)<br>`fun `[`Uri`](./index.md)`.port(): `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`?` |
| [queries](../queries.md) | `fun `[`Uri`](./index.md)`.queries(): `[`Parameters`](../-parameters.md) |
| [query](../query.md) | `fun `[`Uri`](./index.md)`.query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](./index.md) |
| [removeQuery](../remove-query.md) | `fun `[`Uri`](./index.md)`.removeQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [with](../with.md) | `fun <T> `[`T`](../with.md#T)`.with(vararg modifiers: (`[`T`](../with.md#T)`) -> `[`T`](../with.md#T)`): `[`T`](../with.md#T) |
