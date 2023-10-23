# Step Name -> process a go hard-code on an external host
## Component Denominator -> generic

## Component Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Documentation



### Parameters

* __documentation__
```

```

* accountLabels
```
{"external host user's private key":"coderunner-private-key"}
```

* capsule
```
coderunner-2.0
```

* capsuleCollection
```
demo
```

* capsuleCollectionVersion
```
1
```

* capsuleVersionMajor
```
2
```

* capsuleVersionMinor
```
0
```

* id
```
3af53332-a2a8-4e5b-b2a3-f3c54ba6bbb5
```

* name
```
capsule-v1-demo-demo-coderunner-2.0
```

* params
```
{"engine":"go","args":"run","ext":"go","codeargs":"","isjson":true,"code":"package main\nimport (\n    \"fmt\"\n    \"encoding/json\"\n)\ntype Output struct {\n Message string `json:\"message\"`\n}\nfunc main() {\n    myOutput := Output{\"Hello World!\"}\n    bytes, _ := json.Marshal(myOutput)\n    fmt.Println(string(bytes))\n}","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"}
```

* stepName
```
process a go hard-code on an external host
```

* type
```
capsule
```


## RAW Object

```
{"type":"capsule","name":"capsule-v1-demo-demo-coderunner-2.0","capsuleCollection":"demo","capsuleCollectionVersion":1,"capsule":"coderunner-2.0","capsuleVersionMajor":2,"capsuleVersionMinor":0,"stepName":"process a go hard-code on an external host","params":{"engine":"go","args":"run","ext":"go","codeargs":"","isjson":true,"code":"package main\nimport (\n    \"fmt\"\n    \"encoding/json\"\n)\ntype Output struct {\n Message string `json:\"message\"`\n}\nfunc main() {\n    myOutput := Output{\"Hello World!\"}\n    bytes, _ := json.Marshal(myOutput)\n    fmt.Println(string(bytes))\n}","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"},"id":"3af53332-a2a8-4e5b-b2a3-f3c54ba6bbb5","__documentation__":"","accountLabels":{"external host user's private key":"coderunner-private-key"}}
```