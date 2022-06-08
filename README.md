# MAVEN Repository

This repo is supporting java library in gradle or maven build.

## Gradle setting - add repository
```groovy
repositories {
    mavenCentral()
    .
    .
    .
    maven {
        url "https://raw.githubusercontent.com/iptv-devops/maven-repository/main"
        metadataSources {
            gradleMetadata()
        }
    }
}
```
