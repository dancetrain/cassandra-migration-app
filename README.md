# Small app to demonstrate how schema migration library works

## The problem
1. Compile your schema manager app
2. Upload to server
3. Run
4. Get next message in logs

```
[main] INFO org.cognitor.cassandra.migration.MigrationRepository - Found 0 migration scripts
```

## Examples
java -jar example/cassandra-migration-file.jar
java -jar example/cassandra-migration-jar.jar
