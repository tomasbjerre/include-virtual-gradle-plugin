# Include Virtual Gradle Plugin

[![Maven Central](https://img.shields.io/maven-central/v/se.bjurr.gradle/include-virtual.svg?label=Maven%20Central)](https://central.sonatype.com/artifact/se.bjurr.gradle/include-virtual)

A settings plugin. Apply it in `settings.gradle` and it will provide `includeVirtual` method. It:

- Creates project folders, if they don't exist.
- Includes the projects, with `include`.

Gradle 9 changed the behavior of `include` so that it now fails if the given project folder does not exist.
