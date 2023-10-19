# Step Name -> JSON Generator
## Component Denominator -> json-generator-connector

## Component Description

JSON Generator (Mock) creates a JSON object. This component accepts any input.

Check this component official documentation: [json-generator-connector](https://docs.digibee.com/documentation/components/tools/json-generator "Digibee json-generator-connector documentation")

## Component Configuration Details
### Documentation

O parâmetro referente à documentação descritiva do componente não foi preenchido ou está indisponível para este componente.

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
{"name":"json-generator-connector","type":"connector","stepName":"JSON Generator","params":{"json":"{{ TOJSON(message.stdout) }}","failOnError":false},"id":"b294b6c5-a3f3-4b03-bee9-a1b795c71458"}
```