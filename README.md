## This is the pipeline dgb-code-runner README:
## This is the pipeline components tree:
```bash
└── 00-Parallel Execution (parallel-execution-connector)
    ├── execution-execution-golang
    │   ├── 00-Go B64 Code (json-generator-connector)
    │   ├── 01-Execute Go Command (ssh-remote-command-connector)
    │   └── 02-JSON Generator (json-generator-connector)
    └── execution-execution-python
        ├── 00-Python B64 Code (json-generator-connector)
        ├── 01-Execute Python Command (ssh-remote-command-connector)
        └── 02-JSON Generator (json-generator-connector)

```
