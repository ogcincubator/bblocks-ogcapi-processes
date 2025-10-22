
# LandingPage (Response)

`ogc.api.processes.v1.responses.LandingPage` *v0.1*

None

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
content:
  application/json:
    schema:
      $ref: https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/schemas/landingPage/schema.yaml
  text/html:
    schema:
      type: string
description: 'The landing page provides links to the API definition

  (link relations `service-desc` and `service-doc`),

  the Conformance declaration (path `/conformance`,

  link relation `http://www.opengis.net/def/rel/ogc/1.0/conformance`), and to other
  resources.'

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/LandingPage/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-ogcapi-processes/build/annotated/api/processes/v1/responses/LandingPage/schema.yaml)

## Sources

* [OGC API Features - Part 1 - Core corrigendum](https://docs.ogc.org/is/17-069r4/17-069r4.html)

# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-ogcapi-processes](https://github.com/ogcincubator/bblocks-ogcapi-processes)
* Path: `_sources/v1/responses/LandingPage`

