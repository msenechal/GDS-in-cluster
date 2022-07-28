# GDS-in-cluster
Running GDS in a cluster

# Things to do before running:

Download the [Neo4j GDS plugin](https://neo4j.com/download-center/#graph-data-science) and copy it to the read-gds/plugins folder

Put a valid GDS license key in read-gds/license/gds.license



# Run

```docker
docker compose -f .\gds-cluster.yml create
docker compose -f .\gds-cluster.yml start
```

# Remove everything

```docker
docker compose -f .\gds-cluster.yml stop
docker compose -f .\gds-cluster.yml rm
```