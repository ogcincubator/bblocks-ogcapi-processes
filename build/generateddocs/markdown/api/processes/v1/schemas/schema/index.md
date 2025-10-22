
# schema (Schema)

`ogc.api.processes.v1.schemas.schema` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
- additionalProperties: false
  properties:
    additionalProperties:
      default: true
      oneOf:
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
      - type: boolean
    allOf:
      items:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
      type: array
    anyOf:
      items:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
      type: array
    contentEncoding:
      type: string
    contentMediaType:
      type: string
    contentSchema:
      type: string
    default: {}
    deprecated:
      default: false
      type: boolean
    description:
      type: string
    enum:
      items: {}
      minItems: 1
      type: array
      uniqueItems: false
    example: {}
    exclusiveMaximum:
      default: false
      type: boolean
    exclusiveMinimum:
      default: false
      type: boolean
    format:
      type: string
    items:
      oneOf:
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
    maxItems:
      minimum: 0
      type: integer
    maxLength:
      minimum: 0
      type: integer
    maxProperties:
      minimum: 0
      type: integer
    maximum:
      type: number
    minItems:
      default: 0
      minimum: 0
      type: integer
    minLength:
      default: 0
      minimum: 0
      type: integer
    minProperties:
      default: 0
      minimum: 0
      type: integer
    minimum:
      type: number
    multipleOf:
      exclusiveMinimum: 0
      type: number
    not:
      oneOf:
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
      - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
    nullable:
      default: false
      type: boolean
    oneOf:
      items:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
      type: array
    pattern:
      format: regex
      type: string
    properties:
      additionalProperties:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml
        - $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/reference/schema.yaml
      type: object
    readOnly:
      default: false
      type: boolean
    required:
      items:
        type: string
      minItems: 1
      type: array
      uniqueItems: true
    title:
      type: string
    type:
      enum:
      - array
      - boolean
      - integer
      - number
      - object
      - string
      type: string
    uniqueItems:
      default: false
      type: boolean
    writeOnly:
      default: false
      type: boolean
  type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/schema/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/schema`

