[http4k](../index.md) / [org.http4k.openapi.v2](index.md) / [flatten](./flatten.md)

# flatten

`fun `[`OpenApi2Spec`](-open-api2-spec/index.md)`.flatten(): `[`OpenApi2Spec`](-open-api2-spec/index.md)

For all parameters which are common (and represented in the paths as Refs), inline the content into the path so
we can tell the type without looking up from the "global" list

