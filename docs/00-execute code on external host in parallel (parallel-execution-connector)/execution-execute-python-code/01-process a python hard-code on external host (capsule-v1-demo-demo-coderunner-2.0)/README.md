# Step Name -> process a python hard-code on external host
## Component Denominator -> generic

## Component Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Documentation

O parâmetro referente à documentação descritiva do componente não foi preenchido ou está indisponível para este componente.

### Parameters

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
916c2a80-1a7d-4bca-88f0-f45cc074f998
```

* name
```
capsule-v1-demo-demo-coderunner-2.0
```

* params
```
{"engine":"python3","args":"","ext":"py","codeargs":"","isjson":true,"code":"import json\n\n# some JSON:\nx = '{\"message\":\"Hello World!\"}'\n\n# print the JSON message:\nprint(x)","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"}
```

* stepName
```
process a python hard-code on external host
```

* type
```
capsule
```


## RAW Object

```
{"type":"capsule","name":"capsule-v1-demo-demo-coderunner-2.0","capsuleCollection":"demo","capsuleCollectionVersion":1,"capsule":"coderunner-2.0","capsuleVersionMajor":2,"capsuleVersionMinor":0,"stepName":"process a python hard-code on external host","params":{"engine":"python3","args":"","ext":"py","codeargs":"","isjson":true,"code":"import json\n\n# some JSON:\nx = '{\"message\":\"Hello World!\"}'\n\n# print the JSON message:\nprint(x)","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"},"id":"916c2a80-1a7d-4bca-88f0-f45cc074f998","accountLabels":{"external host user's private key":"coderunner-private-key"}}
```