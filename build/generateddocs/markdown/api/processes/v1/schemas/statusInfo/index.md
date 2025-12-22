
# statusInfo schema (Schema)

`ogc.api.processes.v1.schemas.statusInfo` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  created:
    format: date-time
    type: string
  finished:
    format: date-time
    type: string
  jobID:
    type: string
  links:
    items:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/link/schema.yaml
    type: array
  message:
    type: string
  processID:
    type: string
  progress:
    maximum: 100
    minimum: 0
    type: integer
  started:
    format: date-time
    type: string
  status:
    $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/statusCode/schema.yaml
  type:
    enum:
    - process
    type: string
  updated:
    format: date-time
    type: string
required:
- jobID
- status
- type
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/statusInfo/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/statusInfo/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/statusInfo`

