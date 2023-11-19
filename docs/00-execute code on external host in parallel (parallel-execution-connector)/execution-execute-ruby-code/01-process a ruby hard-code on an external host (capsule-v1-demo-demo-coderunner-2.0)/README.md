# Step Name -> process a ruby hard-code on an external host
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
1be76dae-1dd1-43ed-9424-3b76c49baeb2
```

* name
```
capsule-v1-demo-demo-coderunner-2.0
```

* params
```
{"engine":"ruby","args":"","ext":"rb","codeargs":"","isjson":false,"code":"puts \"Hello World!\"","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"}
```

* stepName
```
process a ruby hard-code on an external host
```

* type
```
capsule
```


## RAW Object

```
{"type":"capsule","name":"capsule-v1-demo-demo-coderunner-2.0","capsuleCollection":"demo","capsuleCollectionVersion":1,"capsule":"coderunner-2.0","capsuleVersionMajor":2,"capsuleVersionMinor":0,"stepName":"process a ruby hard-code on an external host","params":{"engine":"ruby","args":"","ext":"rb","codeargs":"","isjson":false,"code":"puts \"Hello World!\"","hostname":"{{global.ahs-ssh-hostname}}","port":"{{global.ext-host-code-port}}","username":"{{global.ext-host-code-username}}"},"id":"1be76dae-1dd1-43ed-9424-3b76c49baeb2","accountLabels":{"external host user's private key":"coderunner-private-key"}}
```