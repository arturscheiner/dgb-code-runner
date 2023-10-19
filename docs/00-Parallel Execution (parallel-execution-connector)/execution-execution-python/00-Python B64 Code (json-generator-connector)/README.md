# Step Name -> Python B64 Code
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
{
    "b64code": "aW1wb3J0IGpzb24KCiMgc29tZSBKU09OOgp4ID0gJ3sibWVzc2FnZSI6IkhlbGxvIFdvcmxkISJ9JwoKIyBwcmludCB0aGUgSlNPTiBtZXNzYWdlOgpwcmludCh4KQo=",
    "language": "python3",
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
{"name":"json-generator-connector","type":"connector","stepName":"Python B64 Code","params":{"json":"{\n    \"b64code\": \"aW1wb3J0IGpzb24KCiMgc29tZSBKU09OOgp4ID0gJ3sibWVzc2FnZSI6IkhlbGxvIFdvcmxkISJ9JwoKIyBwcmludCB0aGUgSlNPTiBtZXNzYWdlOgpwcmludCh4KQo=\",\n    \"language\": \"python3\",\n    \"args\": \"\",\n    \"ext\": \"py\"\n}","failOnError":false},"id":"aaa83553-76b5-4a4a-b050-c82fab0b10c9"}
```