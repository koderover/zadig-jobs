## Update nacos configuration

The `nacos-update-config` job let you update nacos configuration in a workflow

### build image

```
make build
```

### Parameters

* **SERVER_IP:**: The nacos host domain.
* **SERVER_PORT:**: The nacos host port.
* **TENANT_ID:**: The nacos namespace ID.
* **DATA_ID:**: The nacos configuration ID.
* **GROUP:**: The nacos configuration group.
* **TYPE:**: The nacos configuration type. _e.g:_ `json`
* **USER_NAME:**: The nacos user name.
* **PASSWORD:**: The nacos password.
* **SCHEMA:**: The nacos host schema. _e.g:_ `http`
* **CONTENT:**: The configuration to update.
