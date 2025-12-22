
# inputDescription schema (Schema)

`ogc.api.processes.v1.schemas.inputDescription` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Examples

### Complex object with a reference to a BBlock
In this case clients should determine if they recognise the BBlock identifier and can address it.
#### json
```json
{
  "@context": {
    "op": "http://test-data/cafe-walk/observables/"
  },
  "@id": "op:areaOfInterest",
  "title": "BBOX",
  "description": "BBOX via schema ref",
  "minOccurs": 1,
  "schema": {
    "$ref": "bblocks://ogc.geo.common.parameters.bbox"
  }
}
```

#### jsonld
```jsonld
{
  "@context": [
    "https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/inputDescription/context.jsonld",
    {
      "op": "http://test-data/cafe-walk/observables/"
    }
  ],
  "@id": "op:areaOfInterest",
  "title": "BBOX",
  "description": "BBOX via schema ref",
  "minOccurs": 1,
  "schema": {
    "$ref": "bblocks://ogc.geo.common.parameters.bbox"
  }
}
```

#### ttl
```ttl
@prefix op: <http://test-data/cafe-walk/observables/> .
@prefix proc: <https://w3id.org/ogc/api/processes/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

op:areaOfInterest proc:description "BBOX via schema ref" ;
    proc:minOccurs 1 ;
    proc:schema [ proc:ref <bblocks://ogc.geo.common.parameters.bbox> ] ;
    proc:title "BBOX" .


```

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
      x-jsonld-id: https://w3id.org/ogc/api/processes/maxOccurs
    minOccurs:
      default: 1
      type: integer
      x-jsonld-id: https://w3id.org/ogc/api/processes/minOccurs
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
      x-jsonld-id: https://w3id.org/ogc/api/processes/schema
  required:
  - schema
  type: object
x-jsonld-extra-terms:
  title: http://purl.org/dc/terms/title
  description: http://purl.org/dc/terms/description
  keywords: https://w3id.org/ogc/api/processes/keywords
  nullable: https://w3id.org/ogc/api/processes/nullable
  type: https://w3id.org/ogc/api/processes/type
  $ref:
    x-jsonld-id: https://w3id.org/ogc/api/processes/ref
    x-jsonld-type: '@id'
  default:
    x-jsonld-id: https://w3id.org/ogc/api/processes/default
    x-jsonld-type: '@json'
  enum:
    x-jsonld-id: https://w3id.org/ogc/api/processes/enum
    x-jsonld-container: '@set'
x-jsonld-vocab: https://w3id.org/ogc/api/processes/
x-jsonld-prefixes:
  dct: http://purl.org/dc/terms/
  proc: https://w3id.org/ogc/api/processes/

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/inputDescription/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/inputDescription/schema.yaml)


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
[context.jsonld](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/inputDescription/context.jsonld)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/inputDescription`

