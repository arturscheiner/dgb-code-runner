# Step Name -> Execute Python Command
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
{"sshAccount":"ssh-ahs-coderunner-key"}
```

* id
```
f72acc44-fca4-46f1-8fd9-128e351b8b92
```

* name
```
ssh-remote-command-connector
```

* params
```
{"username":"coderunner","host":"lab.oobly.com.br","port":"31022","environmentVariablesRawMode":false,"environmentVariables":"[]","command":"echo \"{{ message.b64code }}\" > /tmp/code.b64\necho \"$(base64 -d /tmp/code.b64)\" > ~/code.{{ message.ext }}\nLANGUAGE=\"{{ message.language }}\"\n$(echo $LANGUAGE) {{ message.args }} code.{{ message.ext }}","ignoreOutput":false,"stdoutAsFile":false,"stderrAsFile":false,"connectTimeout":30000,"serverAliveInterval":30000,"failOnError":false}
```

* stepName
```
Execute Python Command
```

* type
```
connector
```


## RAW Object

```
{"type":"connector","name":"ssh-remote-command-connector","stepName":"Execute Python Command","accountLabels":{"sshAccount":"ssh-ahs-coderunner-key"},"params":{"username":"coderunner","host":"lab.oobly.com.br","port":"31022","environmentVariablesRawMode":false,"environmentVariables":"[]","command":"echo \"{{ message.b64code }}\" > /tmp/code.b64\necho \"$(base64 -d /tmp/code.b64)\" > ~/code.{{ message.ext }}\nLANGUAGE=\"{{ message.language }}\"\n$(echo $LANGUAGE) {{ message.args }} code.{{ message.ext }}","ignoreOutput":false,"stdoutAsFile":false,"stderrAsFile":false,"connectTimeout":30000,"serverAliveInterval":30000,"failOnError":false},"id":"f72acc44-fca4-46f1-8fd9-128e351b8b92"}
```