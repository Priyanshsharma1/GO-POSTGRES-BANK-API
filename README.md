# GO-POSTGRES-BANK-API
Bank CRUD Api with JWT authentcation and postgres docker instance

Setup with 
```go
go mod init -repo name
go mod tidy
make run
```
For running Postgres container use docker desktop or use cmd line 

```bash
docker run --name <container-name> -e POSTGRES_PASSWORD=<password> -p <host-port>:<container-port> -d postgres:<tag>
```
