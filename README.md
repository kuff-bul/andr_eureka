# andr-eureka

Eureka discovery server for the `andr` Spring services.

## Run

```powershell
mvn spring-boot:run
```

The server starts on `http://localhost:8761` by default.

You can override the port:

```powershell
$env:SERVER_PORT = "8762"
mvn spring-boot:run
```
