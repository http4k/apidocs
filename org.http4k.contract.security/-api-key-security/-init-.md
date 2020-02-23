[http4k](../../index.md) / [org.http4k.contract.security](../index.md) / [ApiKeySecurity](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`ApiKeySecurity(param: `[`Lens`](../../org.http4k.lens/-lens/index.md)`<`[`Request`](../../org.http4k.core/-request/index.md)`, T>, validateKey: (T) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, authorizeOptionsRequests: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true, name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "api_key")`

Checks the presence of the named Api Key parameter. Filter returns 401 if Api-Key is not found in request.

Default implementation of ApiKey. Includes an option to NOT authorise OPTIONS requests, which is
currently not enabled for OpenAPI.

