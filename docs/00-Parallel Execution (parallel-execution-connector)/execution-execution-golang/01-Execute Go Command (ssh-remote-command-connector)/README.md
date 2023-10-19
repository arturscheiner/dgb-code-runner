# Step Name -> Execute Go Command
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
{"sshAccount":"ssh-ahs-coderunner-key"}
```

* id
```
5107b62f-d787-407a-ba68-55114685c0d1
```

* name
```
ssh-remote-command-connector
```

* params
```
{"username":"coderunner","host":"{{global.ahs-ssh-hostname}}","port":"{{global.ahs-ssh-port}}","environmentVariablesRawMode":false,"environmentVariables":"[]","command":"echo \"{{ message.b64code }}\" > /tmp/code.b64\necho \"$(base64 -d /tmp/code.b64)\" > ~/code.{{ message.ext }}\nLANGUAGE=\"{{ message.language }}\"\n$(echo $LANGUAGE) {{ message.args }} code.{{ message.ext }}","ignoreOutput":false,"stdoutAsFile":false,"stderrAsFile":false,"connectTimeout":30000,"serverAliveInterval":30000,"failOnError":false}
```

* stepName
```
Execute Go Command
```

* type
```
connector
```


## RAW Object

```
{"type":"connector","name":"ssh-remote-command-connector","stepName":"Execute Go Command","accountLabels":{"sshAccount":"ssh-ahs-coderunner-key"},"params":{"username":"coderunner","host":"{{global.ahs-ssh-hostname}}","port":"{{global.ahs-ssh-port}}","environmentVariablesRawMode":false,"environmentVariables":"[]","command":"echo \"{{ message.b64code }}\" > /tmp/code.b64\necho \"$(base64 -d /tmp/code.b64)\" > ~/code.{{ message.ext }}\nLANGUAGE=\"{{ message.language }}\"\n$(echo $LANGUAGE) {{ message.args }} code.{{ message.ext }}","ignoreOutput":false,"stdoutAsFile":false,"stderrAsFile":false,"connectTimeout":30000,"serverAliveInterval":30000,"failOnError":false},"id":"5107b62f-d787-407a-ba68-55114685c0d1","__documentation__":""}
```