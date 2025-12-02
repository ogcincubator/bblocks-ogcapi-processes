
# processList schema (Schema)

`ogc.api.processes.v1.schemas.processList` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  links:
    items:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/link/schema.yaml
    type: array
  processes:
    items:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/processSummary/schema.yaml
    type: array
required:
- processes
- links
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/processList/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/processList/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "href": {},
    "hreflang": {},
    "rel": {},
    "title": {},
    "type": {},
    "links": {},
    "additionalParameters": {
      "@context": {
        "role": {},
        "parameters": {
          "@context": {
            "name": {},
            "value": {}
          }
        }
      }
    },
    "description": {},
    "keywords": {},
    "metadata": {
      "@context": {
        "role": {}
      }
    },
    "id": {},
    "jobControlOptions": {},
    "outputTransmission": {},
    "version": {},
    "processes": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/processList/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/processList`

