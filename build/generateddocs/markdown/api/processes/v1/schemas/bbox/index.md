
# bbox schema (Schema)

`ogc.api.processes.v1.schemas.bbox` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  bbox:
    items:
      type: number
    oneOf:
    - maxItems: 4
      minItems: 4
    - maxItems: 6
      minItems: 6
    type: array
  crs:
    default: http://www.opengis.net/def/crs/OGC/1.3/CRS84
    enum:
    - http://www.opengis.net/def/crs/OGC/1.3/CRS84
    - http://www.opengis.net/def/crs/OGC/0/CRS84h
    format: uri
    type: string
required:
- bbox
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/bbox/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/bbox/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "bbox": {},
    "crs": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/bbox/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/bbox`

