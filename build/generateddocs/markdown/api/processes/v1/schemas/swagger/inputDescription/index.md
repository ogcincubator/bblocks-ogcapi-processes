
# inputDescription schema (Schema)

`ogc.api.processes.v1.schemas.swagger.inputDescription` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
allOf:
- $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/descriptionType/schema.yaml
- properties:
    maxOccurs:
      oneOf:
      - default: 1
        type: integer
      - enum:
        - unbounded
        type: string
    minOccurs:
      default: 1
      type: integer
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/schema/schema.yaml
  required:
  - schema
  type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/inputDescription/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/inputDescription/schema.yaml)


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
    "maxOccurs": {},
    "minOccurs": {},
    "schema": {},
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/swagger/inputDescription/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/swagger/inputDescription`

