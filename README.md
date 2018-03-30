# NiFi Custom Processors

## Build

```
mvn clean install
```

## Deployment

1. Copy the target/examples-1.0-SNAPSHOT.nar to $NIFI_HOME/lib
2. $NIFI_HOME/bin/nifi.sh stop
3. $NIFI_HOME/bin/nifi.sh start

After Nifi finishes starting you should be able to add it to your flow.

Nifi.rocks will follow up with how to generate unit tests and documentation for your custom processors soon.