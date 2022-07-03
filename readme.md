# Notes

For Cypher Cheat sheet : https://neo4j.com/docs/cypher-cheat-sheet/current/

```
docker run -it -v $(pwd)/datadir:/mnt/h/Data/Matter/Neutron/Downloaded/Neo4j/HM   --publish=7474:7474 --publish=7687:7687   --user="$(id -u):$(id -g)"   -e NEO4J_AUTH=none   --env NEO4JLABS_PLUGINS='["apoc"]'   neo4j:4.4.8
```
```
docker exec -it <containerId> bash
```

In your data dir folder add the required files and it will automatically get reflected in the docker file system inside (left-hand for the first command):  /mnt/h/Data/Matter/Neutron/Downloaded/Neo4j/HM
