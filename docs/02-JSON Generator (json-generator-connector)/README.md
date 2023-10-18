# Step Name -> JSON Generator
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
{{ TOJSON(message.stdout) }}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"JSON Generator","params":{"json":"{{ TOJSON(message.stdout) }}","failOnError":false},"id":"0a4e190f-6882-41c5-b03e-271d3cd302f5","__documentation__":""}
```