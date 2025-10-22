
# exception (Schema)

`ogc.api.processes.v1.schemas.exception` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: true
description: JSON schema for exceptions based on RFC 7807
properties:
  detail:
    type: string
  instance:
    type: string
  status:
    type: integer
  title:
    type: string
  type:
    type: string
required:
- type
title: Exception Schema
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/exception/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/exception/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/exception`

