[http4k](../../index.md) / [org.http4k.cloudnative.env](../index.md) / [Environment](index.md) / [overrides](./overrides.md)

# overrides

`open infix fun overrides(that: `[`Environment`](index.md)`): `[`Environment`](index.md) [(source)](https://github.com/http4k/http4k/blob/master/http4k-cloudnative/src/main/kotlin/org/http4k/cloudnative/env/Environment.kt#L37)

Overlays the configuration set in this Environment on top of the values in the passed Environment.
Used to chain: eg. Local File -&gt; System Properties -&gt; Env Properties -&gt; Defaults

