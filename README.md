# dinowernli@'s Maven Repos

This repository contains binary artifacts for Java and Scala. They are served using the `raw` endpoints of Github.

To use this repository in your projects, add the following to your `pom.xml` (or equivalent config):

```xml
<repositories>
  ...
  <repository>
    <id>dinowernli-github-repo</id>
    <url>https://raw.github.com/dinowernli/maven-repos/master</url>
  </repository>
  ...
</repositories>
<dependencies>
```

## Projects

 * [java-grpc-prometheus](https://github.com/dinowernli/java-grpc-prometheus) - gRPC interceptors which increment Prometheus counters for monitoring


## License

These are just binary artifacts, each of them contains metadata mentioning the respective license.
