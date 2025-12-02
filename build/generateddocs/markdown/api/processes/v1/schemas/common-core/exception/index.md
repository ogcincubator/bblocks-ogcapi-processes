
# Schema for exception schema (Schema)

`ogc.api.processes.v1.schemas.common-core.exception` *v0.1*

This building block corresponds to the schema for an OGC API Features exception

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
type: object
required:
- code
properties:
  code:
    type: string
  description:
    type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/common-core/exception/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/common-core/exception/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "code": {},
    "description": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/common-core/exception/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/common-core/exception`

