
# link schema (Schema)

`ogc.api.processes.v1.schemas.link` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  href:
    type: string
  hreflang:
    example: en
    type: string
  rel:
    example: service
    type: string
  title:
    type: string
  type:
    example: application/json
    type: string
required:
- href
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/link/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/link/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "href": {},
    "hreflang": {},
    "rel": {},
    "title": {},
    "type": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/link/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/link`

