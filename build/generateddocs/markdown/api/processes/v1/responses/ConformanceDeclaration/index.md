
# ConformanceDeclaration (Response)

`ogc.api.processes.v1.responses.ConformanceDeclaration` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
content:
  application/json:
    example:
      conformsTo:
      - http://www.opengis.net/spec/ogcapi-processes/1.0/conf/core
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/confClasses/schema.yaml
  text/html:
    schema:
      type: string
description: 'The URIs of all conformance classes supported by the server.


  To support "generic" clients that want to access multiple

  OGC API - Processes implementations - and not "just" a specific

  API / server, the server declares the conformance

  classes it implements and conforms to.'

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ConformanceDeclaration/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ConformanceDeclaration/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/responses/ConformanceDeclaration`

