# Step Name -> log info on executing python code
## Component Denominator -> log-connector

## Component Description

Log allows the creation of log registers inside a pipeline. It helps in the generation of steps traceability when you want so.

Check this component official documentation: [log-connector](https://docs.digibee.com/documentation/components/tools/log "Digibee log-connector documentation")

## Component Configuration Details
### Documentation



### Parameters

* logLevel
```
INFO
```

* message
```
Info processing message {{ message.$ }}
```


## RAW Object

```
{"type":"connector","name":"log-connector","stepName":"log info on executing python code","params":{"logLevel":"INFO","message":"Info processing message {{ message.$ }}"},"id":"bf7a95d7-0244-4a7e-9bbd-1150d1bba33c","__documentation__":""}
```