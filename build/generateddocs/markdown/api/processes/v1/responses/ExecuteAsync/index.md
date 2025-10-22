
# ExecuteAsync (Response)

`ogc.api.processes.v1.responses.ExecuteAsync` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
content:
  application/json:
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/statusInfo/schema.yaml
description: Started asynchronous execution. Created job.
headers:
  Location:
    description: URL to check the status of the execution/job.
    schema:
      type: string
  Preference-Applied:
    description: The preference applied to execute the process asynchronously (see.
      RFC 2740).
    schema:
      type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ExecuteAsync/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ExecuteAsync/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/responses/ExecuteAsync`

