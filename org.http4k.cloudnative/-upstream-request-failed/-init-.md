[http4k](../../index.md) / [org.http4k.cloudnative](../index.md) / [UpstreamRequestFailed](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`UpstreamRequestFailed(message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`

This hierarchy of exceptions should be used to indicate that an upstream remote system has failed with a
non-successful status code which caused us to stop processing. They are designed to be used with the
Server and Client filters which will allow automatic handling and propagation of erroneous responses from
upstream.

