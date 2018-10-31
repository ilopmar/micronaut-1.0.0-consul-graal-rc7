# Micronaut and consul #

Application created with Micronaut 1.0.0 with Consul and Graal-rc7 support

To build the native image:
```
./gradlew assemble
docker build . -t micronaut-graal-consul
```
