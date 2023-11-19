## This is the pipeline dgb-code-runner README:
## This is the pipeline components tree:
```bash
└── 00-execute code on external host in parallel (parallel-execution-connector)
    ├── execution-execute-go-code
    │   ├── 00-log info on executing go code (log-connector)
    │   └── 01-process a go hard-code on an external host (capsule-v1-demo-demo-coderunner-2.0)
    ├── execution-execute-python-code
    │   ├── 00-log info on executing python code (log-connector)
    │   └── 01-process a python hard-code on external host (capsule-v1-demo-demo-coderunner-2.0)
    └── execution-execute-ruby-code
        ├── 00-log info on executing ruby code (log-connector)
        └── 01-process a ruby hard-code on an external host (capsule-v1-demo-demo-coderunner-2.0)

```
