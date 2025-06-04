# Project Documentation

This document provides an overview of the repository structure and how to work with the design pattern samples.

## Repository Structure

The project is organized as a multi-module Maven build. Each design pattern resides in its own module under the project root. Within a pattern module you'll find the source code under `src/main/java` and short documentation in an `index.md` file.

```
<pattern-name>/
  ├── pom.xml
  ├── src/
  │   └── main/java/...
  └── index.md
```

The root `pom.xml` aggregates all pattern modules so you can build everything in one command.

## Building the Project

To compile all examples and run the available tests, use Maven from the project root:

```bash
mvn clean install
```

This command builds every pattern module and executes any unit tests they contain.

## Contributing

Contributions are welcome! See the main `README.md` for details on how to get started and a link to the project's developer wiki.

