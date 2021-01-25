[http4k](../../index.md) / [org.http4k.security.oauth.testing](../index.md) / [FakeOAuthServer](index.md) / [invoke](./invoke.md)

# invoke

`operator fun invoke(authPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, tokenPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone(), accessCodePrefix: (`[`AuthorizationCode`](../../org.http4k.security.oauth.server/-authorization-code/index.md)`) -> `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = { "OAUTH_" + it.value.reversed() }): `[`HttpHandler`](../../org.http4k.core/-http-handler.md)