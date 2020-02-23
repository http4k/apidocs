[http4k](../../../index.md) / [org.http4k.filter](../../index.md) / [CachingFilters](../index.md) / [Response](./index.md)

# Response

`object Response`

These filters operate on Responses (post-flight)

### Types

| Name | Summary |
|---|---|
| [AddETag](-add-e-tag/index.md) | Hash algo stolen from http://stackoverflow.com/questions/26423662/scalatra-response-hmac-calulation By default, only applies when the status code of the response is &lt; 400. This is overridable.`object AddETag` |
| [FallbackCacheControl](-fallback-cache-control/index.md) | Applies the passed cache timings (Cache-Control, Expires, Vary) to responses, but only if they are not there already. Use this for adding default cache settings. By default, only applies when the status code of the response is &lt; 400. This is overridable.`object FallbackCacheControl` |
| [MaxAge](-max-age/index.md) | By default, only applies when the status code of the response is &lt; 400. This is overridable.`object MaxAge` |
| [NoCache](-no-cache/index.md) | By default, only applies when the status code of the response is &lt; 400. This is overridable and useful - For example you could combine this with a MaxAge for everything &gt;= 400`object NoCache` |
