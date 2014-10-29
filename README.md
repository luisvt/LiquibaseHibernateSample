LiquibaseHibernateSample
======================

Very simple demonstration of using liquibase-hibernate with liquibase-maven-plugin.

Usage:

 * Generate diff:

```
mvn -Pdb-diff
```

 * Sync Database:

```
mvn -Pdb-sync
```

 * Rollback Database:

```
mvn -Pdb-rollback
```
