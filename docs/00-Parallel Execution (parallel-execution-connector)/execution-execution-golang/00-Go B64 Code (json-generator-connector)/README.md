# Step Name -> Go B64 Code
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
    "b64code": "cGFja2FnZSBtYWluCmltcG9ydCAoCiAgICAiZm10IgogICAgImVuY29kaW5nL2pzb24iCikKdHlwZSBPdXRwdXQgc3RydWN0IHsKCU1lc3NhZ2Ugc3RyaW5nIGBqc29uOiJtZXNzYWdlImAKfQpmdW5jIG1haW4oKSB7CiAgICBteU91dHB1dCA6PSBPdXRwdXR7IkhlbGxvIFdvcmxkISJ9CiAgICBieXRlcywgXyA6PSBqc29uLk1hcnNoYWwobXlPdXRwdXQpCiAgICBmbXQuUHJpbnRsbihzdHJpbmcoYnl0ZXMpKQp9Cg==",
    "language": "go",
    "args": "run",
    "ext": "go"
}
```

* FailOnError
If true will stop pipeline with an error, if false will let the pipeline continue but the output will show a property success with value false.

```
false
```

## RAW Object

```
{"name":"json-generator-connector","type":"connector","stepName":"Go B64 Code","params":{"json":"{\n    \"b64code\": \"cGFja2FnZSBtYWluCmltcG9ydCAoCiAgICAiZm10IgogICAgImVuY29kaW5nL2pzb24iCikKdHlwZSBPdXRwdXQgc3RydWN0IHsKCU1lc3NhZ2Ugc3RyaW5nIGBqc29uOiJtZXNzYWdlImAKfQpmdW5jIG1haW4oKSB7CiAgICBteU91dHB1dCA6PSBPdXRwdXR7IkhlbGxvIFdvcmxkISJ9CiAgICBieXRlcywgXyA6PSBqc29uLk1hcnNoYWwobXlPdXRwdXQpCiAgICBmbXQuUHJpbnRsbihzdHJpbmcoYnl0ZXMpKQp9Cg==\",\n    \"language\": \"go\",\n    \"args\": \"run\",\n    \"ext\": \"go\"\n}","failOnError":false},"id":"9459e133-b96b-4f41-890e-da9bf9221345"}
```