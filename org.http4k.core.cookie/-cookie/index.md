[http4k](../../index.md) / [org.http4k.core.cookie](../index.md) / [Cookie](./index.md)

# Cookie

`data class Cookie`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Cookie(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, maxAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`? = null, expires: `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`? = null, domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`? = null, secure: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, httpOnly: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, sameSite: `[`SameSite`](../-same-site/index.md)`? = null)` |

### Properties

| Name | Summary |
|---|---|
| [domain](domain.md) | `val domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [expires](expires.md) | `val expires: `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`?` |
| [httpOnly](http-only.md) | `val httpOnly: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [maxAge](max-age.md) | `val maxAge: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`?` |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [path](path.md) | `val path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [sameSite](same-site.md) | `val sameSite: `[`SameSite`](../-same-site/index.md)`?` |
| [secure](secure.md) | `val secure: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [value](value.md) | `val value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [domain](domain.md) | `fun domain(domain: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md) |
| [expires](expires.md) | `fun expires(date: `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`): `[`Cookie`](./index.md) |
| [fullCookieString](full-cookie-string.md) | `fun fullCookieString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [httpOnly](http-only.md) | `fun httpOnly(): `[`Cookie`](./index.md) |
| [keyValueCookieString](key-value-cookie-string.md) | `fun keyValueCookieString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [maxAge](max-age.md) | `fun maxAge(seconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Cookie`](./index.md) |
| [path](path.md) | `fun path(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md) |
| [sameSite](same-site.md) | `fun sameSite(sameSite: `[`SameSite`](../-same-site/index.md)`): `[`Cookie`](./index.md) |
| [secure](secure.md) | `fun secure(): `[`Cookie`](./index.md) |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | `fun parse(cookieValue: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Cookie`](./index.md)`?` |

### Extension Functions

| Name | Summary |
|---|---|
| [invalidate](../invalidate.md) | `fun `[`Cookie`](./index.md)`.invalidate(): `[`Cookie`](./index.md) |
| [shouldBeHttpOnly](../../org.http4k.kotest/should-be-http-only.md) | `fun `[`Cookie`](./index.md)`.shouldBeHttpOnly(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldBeSecure](../../org.http4k.kotest/should-be-secure.md) | `fun `[`Cookie`](./index.md)`.shouldBeSecure(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveDomain](../../org.http4k.kotest/should-have-domain.md) | `infix fun `[`Cookie`](./index.md)`.shouldHaveDomain(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveExpiry](../../org.http4k.kotest/should-have-expiry.md) | `infix fun `[`Cookie`](./index.md)`.shouldHaveExpiry(expected: `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveName](../../org.http4k.kotest/should-have-name.md) | `infix fun `[`Cookie`](./index.md)`.shouldHaveName(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHavePath](../../org.http4k.kotest/should-have-path.md) | `infix fun `[`Cookie`](./index.md)`.shouldHavePath(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveSameSite](../../org.http4k.kotest/should-have-same-site.md) | `infix fun `[`Cookie`](./index.md)`.shouldHaveSameSite(expected: `[`SameSite`](../-same-site/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldHaveValue](../../org.http4k.kotest/should-have-value.md) | `infix fun `[`Cookie`](./index.md)`.shouldHaveValue(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNeverExpire](../../org.http4k.kotest/should-never-expire.md) | `fun `[`Cookie`](./index.md)`.shouldNeverExpire(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotBeHttpOnly](../../org.http4k.kotest/should-not-be-http-only.md) | `fun `[`Cookie`](./index.md)`.shouldNotBeHttpOnly(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotBeSecure](../../org.http4k.kotest/should-not-be-secure.md) | `fun `[`Cookie`](./index.md)`.shouldNotBeSecure(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveDomain](../../org.http4k.kotest/should-not-have-domain.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHaveDomain(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveExpiry](../../org.http4k.kotest/should-not-have-expiry.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHaveExpiry(expected: `[`LocalDateTime`](https://docs.oracle.com/javase/9/docs/api/java/time/LocalDateTime.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveName](../../org.http4k.kotest/should-not-have-name.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHaveName(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHavePath](../../org.http4k.kotest/should-not-have-path.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHavePath(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveSameSite](../../org.http4k.kotest/should-not-have-same-site.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHaveSameSite(expected: `[`SameSite`](../-same-site/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [shouldNotHaveValue](../../org.http4k.kotest/should-not-have-value.md) | `infix fun `[`Cookie`](./index.md)`.shouldNotHaveValue(expected: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
