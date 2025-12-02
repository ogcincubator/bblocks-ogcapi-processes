
# outputDescription schema (Schema)

`ogc.api.processes.v1.schemas.swagger.outputDescription` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
allOf:
- $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/descriptionType/schema.yaml
- properties:
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/schema/schema.yaml
  required:
  - schema
  type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/outputDescription/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/outputDescription/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "additionalParameters": {
      "@context": {
        "href": {},
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
        "href": {},
        "role": {}
      }
    },
    "title": {},
    "schema": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/outputDescription/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/swagger/outputDescription`

