# java-lmstfy-client
Java client for LMSTFY


### Using the SDK

The recommended way to use the SDK for Java in your project is to consume it from Maven.

You can import the SDK into your project as follows:

```
<dependency>
    <groupId>com.meitu</groupId>
    <artifactId>java-lmstfy-client</artifactId>
    <version>1.0.0</version>
</dependency>
```

### Building From Source

You can build it from source using Maven:

```
mvn clean install

# Skip tests, checkstyles, findbugs, etc for quick build
mvn clean install -P quick

```