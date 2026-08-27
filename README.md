# Java Spotless lint

Minimal Maven project for testing Java linting with Spotless. The application itself is not
intended to be functional.

## Prerequisites

- JDK 17 or newer
- Maven

## Check formatting

```bash
mvn spotless:check
```

## Apply formatting

```bash
mvn spotless:apply
```

The lint configuration uses Google Java Format with the `GOOGLE` style, removes unused imports,
and rejects wildcard imports.
