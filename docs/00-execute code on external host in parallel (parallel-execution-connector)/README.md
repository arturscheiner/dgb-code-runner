# Step Name -> execute code on external host in parallel
## Component Denominator -> generic

## Component Description

Digibee components are a powerful way to simplify the process of building integration flows. By using pre-built connectors and logic components, you can quickly and easily create complex integrations that connect different applications and services.

Check Digibee's official documentation: [generic](https://docs.digibee.com/documentation "Digibee documentation")

## Component Configuration Details
### Documentation

O parâmetro referente à documentação descritiva do componente não foi preenchido ou está indisponível para este componente.

### Parameters

* id
```
3632d839-171a-46ab-b229-fb51d86729dc
```

* name
```
parallel-execution-connector
```

* params
```
{"aggregationType":"COLLATE","showExecutionIds":true,"reportExceptions":true,"parallelExecutions":"[{\"description\":\"execute python code\",\"executionId\":\"execute-python-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:bf7a95d7-0244-4a7e-9bbd-1150d1bba33c\"},{\"description\":\"execute go code\",\"executionId\":\"execute-go-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:4cfc6b20-3899-46d3-ad03-4aaf08926a8c\"},{\"description\":\"execute ruby code\",\"executionId\":\"execute-ruby-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:a9a91366-f197-4225-bf63-37062581dfeb\"}]"}
```

* stepName
```
execute code on external host in parallel
```

* type
```
connector
```


## RAW Object

```
{"type":"connector","name":"parallel-execution-connector","stepName":"execute code on external host in parallel","params":{"aggregationType":"COLLATE","showExecutionIds":true,"reportExceptions":true,"parallelExecutions":"[{\"description\":\"execute python code\",\"executionId\":\"execute-python-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:bf7a95d7-0244-4a7e-9bbd-1150d1bba33c\"},{\"description\":\"execute go code\",\"executionId\":\"execute-go-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:4cfc6b20-3899-46d3-ad03-4aaf08926a8c\"},{\"description\":\"execute ruby code\",\"executionId\":\"execute-ruby-code\",\"target\":\"3632d839-171a-46ab-b229-fb51d86729dc:a9a91366-f197-4225-bf63-37062581dfeb\"}]"},"id":"3632d839-171a-46ab-b229-fb51d86729dc"}
```