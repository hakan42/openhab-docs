---
id: jsonpath
label: JsonPath
title: JsonPath - Transformations
type: transform
description: "Extract an element of a JSON string using a [JsonPath expression](https://github.com/jayway/JsonPath#jayway-jsonpath)."
since: 2x
install: auto
---

<!-- Attention authors: Do not edit directly. Please add your changes to the appropriate source repository -->

{% include base.html %}

# JsonPath Transformation Service

Extract an element of a JSON string using a [JsonPath expression](https://github.com/jayway/JsonPath#jayway-jsonpath).

Return `null` if the JsonPath expression could not be found.

## Testing Tools

* [http://jsonpath.com/](http://jsonpath.com/)
* [http://www.jsonquerytool.com/](http://www.jsonquerytool.com/)

## Example

Given the JsonPath expression `$.device.status.temperature`:

| input | output |
|-------|--------|
| `{ "device": { "status": { "temperature": 23.2 }}}` | `23.2` |

