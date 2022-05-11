# Run a ScyllaDB cluster

On your terminal, run the following command:
```
docker-compose up -d
```
Docker-compose will spin up three nodes: scylla1, scylla2 and scylla3. You can access them with the docker command.


To execute nodetool:

```
docker exec -it scylla1 nodetool status
```

To execute CQLSH:
```
docker exec -it scylla1 cqlsh
```
