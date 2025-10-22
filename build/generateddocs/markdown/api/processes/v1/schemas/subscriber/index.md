
# subscriber schema (Schema)

`ogc.api.processes.v1.schemas.subscriber` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Optional URIs for callbacks for this job.


  Support for this parameter is not required and the parameter may be

  removed from the API definition, if conformance class **''callback''**

  is not listed in the conformance declaration under `/conformance`.'
properties:
  failedUri:
    format: uri
    type: string
  inProgressUri:
    format: uri
    type: string
  successUri:
    format: uri
    type: string
required:
- successUrl
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/subscriber/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/subscriber/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/schemas/subscriber`

