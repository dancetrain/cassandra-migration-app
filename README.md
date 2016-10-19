# Small app to demonstrate how schema migration library works

## The problem
1. Compile your schema manager app
2. Upload to server
3. Run
4. Get next message in logs

## Example of usage
```
java -jar example/cassandra-migration-file.jar
[main] INFO org.cognitor.cassandra.migration.MigrationRepository - Found 0 migration scripts
```

```
java -jar example/cassandra-migration-jar.jar
[main] INFO org.cognitor.cassandra.migration.MigrationRepository - Found 2 migration scripts
```
