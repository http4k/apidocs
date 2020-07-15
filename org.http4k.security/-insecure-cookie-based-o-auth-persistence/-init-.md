[http4k](../../index.md) / [org.http4k.security](../index.md) / [InsecureCookieBasedOAuthPersistence](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`InsecureCookieBasedOAuthPersistence(cookieNamePrefix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, cookieValidity: `[`Duration`](https://docs.oracle.com/javase/9/docs/api/java/time/Duration.html)` = Duration.ofHours(3), clock: `[`Clock`](https://docs.oracle.com/javase/9/docs/api/java/time/Clock.html)` = Clock.systemDefaultZone())`

This is an example implementation which stores CSRF and AccessToken values in an INSECURE client-side cookie.
Access-tokens for end-services are fully available to the browser so do not use this in production!

