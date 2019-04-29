# Multi-API support for AutoRest v3 generators

> see https://aka.ms/autorest

``` yaml $(enable-multi-api)
input-file:
  - $(this-folder)/Microsoft.Cdn/stable/2017-10-12/cdn.json
  - $(this-folder)/Microsoft.Cdn/stable/2017-04-02/cdn.json
  - $(this-folder)/Microsoft.Cdn/stable/2016-10-02/cdn.json
  - $(this-folder)/Microsoft.Cdn/stable/2016-04-02/cdn.json
  - $(this-folder)/Microsoft.Cdn/stable/2015-06-01/cdn.json
require: $(this-folder)/../../../profiles/readme.md
```