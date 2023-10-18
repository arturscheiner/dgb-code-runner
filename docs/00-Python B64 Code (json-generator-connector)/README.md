# Step Name -> Python B64 Code
## Component Denominator -> json-generator-connector

## Component Description

JSON Generator (Mock) creates a JSON object. This component accepts any input.

Check this component official documentation: [json-generator-connector](https://docs.digibee.com/documentation/components/tools/json-generator "Digibee json-generator-connector documentation")

## Component Configuration Details
### Documentation



### Parameters

* JSON
The json to generate. Double braces expressions are allowed.

```
{
    "b64code": "CmltcG9ydCBqc29uCgpwZXJzb25fc3RyaW5nID0gJ3sibmFtZSI6ICJCb2IiLCAibGFuZ3VhZ2VzIjogIkVuZ2xpc2giLCAibnVtYmVycyI6IFsyLCAxLjYsIG51bGxdfScKCiMgR2V0dGluZyBkaWN0aW9uYXJ5CnBlcnNvbl9kaWN0ID0ganNvbi5sb2FkcyhwZXJzb25fc3RyaW5nKQoKIyBQcmV0dHkgUHJpbnRpbmcgSlNPTiBzdHJpbmcgYmFjawpwcmludChqc29uLmR1bXBzKHBlcnNvbl9kaWN0LCBpbmRlbnQgPSA0LCBzb3J0X2tleXM9VHJ1ZSkpCg==",
    "language": "python",
    "args": "",
    "ext": "py"
}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"Python B64 Code","params":{"json":"{\n    \"b64code\": \"CmltcG9ydCBqc29uCgpwZXJzb25fc3RyaW5nID0gJ3sibmFtZSI6ICJCb2IiLCAibGFuZ3VhZ2VzIjogIkVuZ2xpc2giLCAibnVtYmVycyI6IFsyLCAxLjYsIG51bGxdfScKCiMgR2V0dGluZyBkaWN0aW9uYXJ5CnBlcnNvbl9kaWN0ID0ganNvbi5sb2FkcyhwZXJzb25fc3RyaW5nKQoKIyBQcmV0dHkgUHJpbnRpbmcgSlNPTiBzdHJpbmcgYmFjawpwcmludChqc29uLmR1bXBzKHBlcnNvbl9kaWN0LCBpbmRlbnQgPSA0LCBzb3J0X2tleXM9VHJ1ZSkpCg==\",\n    \"language\": \"python\",\n    \"args\": \"\",\n    \"ext\": \"py\"\n}","failOnError":false},"id":"2de128cb-2385-44d1-b0bc-7a38fcb33e14","__documentation__":""}
```