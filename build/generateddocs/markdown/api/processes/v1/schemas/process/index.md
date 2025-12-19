
# process schema (Schema)

`ogc.api.processes.v1.schemas.process` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
allOf:
- $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/processSummary/schema.yaml
- properties:
    inputs:
      additionalProperties:
        $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/inputDescription/schema.yaml
    outputs:
      additionalProperties:
        $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/outputDescription/schema.yaml
  type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/process/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/process/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "@vocab": "https://w3id.org/ogc/api/processes/",
    "maxOccurs": "proc:maxOccurs",
    "minOccurs": "proc:minOccurs",
    "schema": {
      "@context": {
        "@vocab": "https://w3id.org/ogc/api/schema/",
        "additionalProperties": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "allOf": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "anyOf": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "items": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "not": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "oneOf": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        },
        "properties": {
          "@context": {
            "@vocab": "https://w3id.org/ogc/api/schema/"
          }
        }
      },
      "@id": "proc:schema"
    },
    "nullable": "proc:nullable",
    "type": "proc:type",
    "$ref": {
      "@id": "proc:ref",
      "@type": "@id"
    },
    "default": {
      "@id": "proc:default",
      "@type": "@json"
    },
    "enum": {
      "@id": "proc:enum",
      "@container": "@set"
    },
    "dct": "http://purl.org/dc/terms/",
    "proc": "https://w3id.org/ogc/api/processes/",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/process/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/process`

