# DataStax Enterprise Java Graph Extension

This package builds on the DataStax Enterprise Java driver, adding functionality for
interacting through the [Apache TinkerPop][tinkerpop] library, via the [DataStax Enterprise Java driver][dsedriver].

* [Apache TinkerPop integration](manual/).

[dsedriver]: http://docs.datastax.com/en/developer/java-driver-dse/1.2/
[tinkerpop]: http://tinkerpop.apache.org/


*The Java DataStax Enterprise Driver can be used solely with DataStax Enterprise. Please consult
[the license](#license).*


## Getting the driver

The driver is available from Maven central:

```xml
<dependency>
  <groupId>com.datastax.cassandra</groupId>
  <artifactId>java-dse-graph</artifactId>
  <version>1.0.0-beta1</version>
</dependency>
```

## Reporting issues

Create a [JIRA](https://datastax-oss.atlassian.net/browse/JAVA) ticket with the "Component/s" field set to "DSE" (or contact DataStax support if you are a DSE customer).

## License

Copyright (C) 2012-2016 DataStax Inc.

The full license terms are available at http://www.datastax.com/terms/datastax-dse-driver-license-terms
