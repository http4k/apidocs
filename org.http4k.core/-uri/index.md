[http4k](../../index.md) / [org.http4k.core](../index.md) / [Uri](./index.md)

# Uri

`data class Uri : `[`Comparable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)`<`[`Uri`](./index.md)`>`

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
| [fragmentParameter](../../org.http4k.security/fragment-parameter.md) | `fun `[`Uri`](./index.md)`.fragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](./index.md) |
| [fragmentParameters](../../org.http4k.security/fragment-parameters.md) | `fun `[`Uri`](./index.md)`.fragmentParameters(): `[`Parameters`](../-parameters.md) |
| [host](../host.md) | `fun `[`Uri`](./index.md)`.host(): `[`Host`](../../org.http4k.cloudnative.env/-host/index.md)<br>`fun `[`Uri`](./index.md)`.host(host: `[`Host`](../../org.http4k.cloudnative.env/-host/index.md)`): `[`Uri`](./index.md) |
| [port](../port.md) | `fun `[`Uri`](./index.md)`.port(port: `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`?): `[`Uri`](./index.md)<br>`fun `[`Uri`](./index.md)`.port(): `[`Port`](../../org.http4k.cloudnative.env/-port/index.md)`?` |
| [queries](../queries.md) | `fun `[`Uri`](./index.md)`.queries(): `[`Parameters`](../-parameters.md) |
| [query](../query.md) | `fun `[`Uri`](./index.md)`.query(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Uri`](./index.md) |
| [removeFragmentParameter](../../org.http4k.security/remove-fragment-parameter.md) | `fun `[`Uri`](./index.md)`.removeFragmentParameter(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [removeQuery](../remove-query.md) | `fun `[`Uri`](./index.md)`.removeQuery(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Uri`](./index.md) |
| [shouldHaveAuthority](../../org.http4k.kotest/should-have-authority.md) | `infix fun `[`Uri`](./index.md)`.shouldHaveAuthority(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveHost](../../org.http4k.kotest/should-have-host.md) | `infix fun `[`Uri`](./index.md)`.shouldHaveHost(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHavePath](../../org.http4k.kotest/should-have-path.md) | `infix fun `[`Uri`](./index.md)`.shouldHavePath(match: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`infix fun `[`Uri`](./index.md)`.shouldHavePath(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`infix fun `[`Uri`](./index.md)`.shouldHavePath(expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHavePort](../../org.http4k.kotest/should-have-port.md) | `infix fun `[`Uri`](./index.md)`.shouldHavePort(expected: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveQuery](../../org.http4k.kotest/should-have-query.md) | `infix fun `[`Uri`](./index.md)`.shouldHaveQuery(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveAuthority](../../org.http4k.kotest/should-not-have-authority.md) | `infix fun `[`Uri`](./index.md)`.shouldNotHaveAuthority(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveHost](../../org.http4k.kotest/should-not-have-host.md) | `infix fun `[`Uri`](./index.md)`.shouldNotHaveHost(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHavePath](../../org.http4k.kotest/should-not-have-path.md) | `infix fun `[`Uri`](./index.md)`.shouldNotHavePath(match: Matcher<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`infix fun `[`Uri`](./index.md)`.shouldNotHavePath(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`infix fun `[`Uri`](./index.md)`.shouldNotHavePath(expected: `[`Regex`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.text/-regex/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHavePort](../../org.http4k.kotest/should-not-have-port.md) | `infix fun `[`Uri`](./index.md)`.shouldNotHavePort(expected: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveQuery](../../org.http4k.kotest/should-not-have-query.md) | `infix fun `[`Uri`](./index.md)`.shouldNotHaveQuery(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
