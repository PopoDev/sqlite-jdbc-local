# SQLite JDBC Driver

SQLite JDBC is a library for accessing and creating [SQLite](https://www.sqlite.org) database files in Java.

This is a fork from xerial/sqlite-jdbc.
- Support local SQLite build, which is useful for testing.

## Build

Build local version:
```bash
make native SQLITE_SOURCE=/path/to/sqlite
```

Build jar:
```bash
mvn package -DskipTests
```
