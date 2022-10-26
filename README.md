# Maven Project Directory Structure

## Learning Goals

- Set up the basic directory structure for a Maven project.
- Explain what each directory is used for.

## Introduction

A Maven project has a
[standard directory structure](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html)
for source code and configurations. We’ll only look at the minimal structure in
this lesson to get started.

## Maven Directory Structure

The following is a basic structure of a Maven project:

```text
└── ~/developer/example-app
		├── pom.xml
		├── src
		│   ├── main
		│   │   ├── java
		│   │   └── resources
		│   └── test
		│       ├── java
		│       └── resources
		└── target
```

- `src/main/java`: this is where the application source files are stored.
- `src/main/resources`: the .properties files, xml config, certificates, and
  other config files are stored here.
- `src/test/java`: the source code for tests are stored here.
- `src/test/resources`: this is where test config files are stored.
- `/target`: this stores the output files of the build process.

There are more directories that you may see in a standard directory. Check out
[the official documentation](https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html)
for a list of these directories.

## Conclusion

We’ve learned to set up the directory structure for adding our source and config
files in a Maven project. We’ll look at how to add dependencies in later
lessons.
