[http4k](../../index.md) / [org.http4k.filter](../index.md) / [ClientFilters](index.md) / [CleanProxy](./-clean-proxy.md)

# CleanProxy

`fun CleanProxy(): <ERROR CLASS>`

This Filter is used to clean the Request and Response when proxying directly to another system. The purpose
of this is to remove any routing metadata that we may have attached to it before sending it onwards.

