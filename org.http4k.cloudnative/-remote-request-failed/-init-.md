[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [RemoteRequestFailed](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`RemoteRequestFailed(status: `[`Status`](../../org.http4k.core/-status/index.md)`, message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, uri: `[`Uri`](../../org.http4k.core/-uri/index.md)`? = null)`

This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a
non-successful status code which caused us to stop processing. They are designed to be used with the
Server and Client filters which will allow automatic handling and propagation of erroneous responses from
upstream.

