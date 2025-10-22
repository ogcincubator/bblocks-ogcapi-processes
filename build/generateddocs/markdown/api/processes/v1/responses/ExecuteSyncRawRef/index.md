
# ExecuteSyncRawRef response (Response)

`ogc.api.processes.v1.responses.ExecuteSyncRawRef` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: Response when negotiate synchronous execution, response=raw, transmissionMode=reference
  and for any number of output values.
headers:
  Link:
    description: One or more Link headers pointing to each raw output.
    schema:
      type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ExecuteSyncRawRef/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/ExecuteSyncRawRef/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/responses/ExecuteSyncRawRef`

