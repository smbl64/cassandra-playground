# Cassandra Playground

Use Docker and Docker-compose to create a 3-node Cassandra cluster.

## Usage

### Start the cluster
```
docker-compose up -d
```

Wait a few minutes, then check if everything is okay:
```
./check-status
```

These three nodes will listen on the following ports: `9042`, `9043`, `9044`.

Use your preferred tool or framework to interact with the cluster. You can also connect to the cluster using `cqlsh`:
```
./run-cqlsh
```

### Stop the cluster

```
docker-compose down -d
```

## License
This code is released under the [MIT License][license].

[license]: ./LICENSE
