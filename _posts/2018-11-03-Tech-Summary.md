> What kinds of tech stack I touched this half a year?

- Framework:
  - Spring:
    - IOC, Bean, AOP, property, many different kinds of annotation
  - Spring Boot
  - Spring Framework
  - Spring Batch
    - Reader, Processor and Writer
    - Tasklet
    - Job
- Database
  - MongoDB
    - Collection, Document, Hash Index, partition, Mongos, Mongod, Mongoclient for java
  - MySQL:
    - Mybatis
    - Partition by mid, memocache.
  - Redis:
    - lettuce redis client
    - `{xxx}` to make hash_slot depends on this mark
    - String, Set, Sorted Set, Hash
  - ElasticSearch:
    - Full text search engine based on Apache Luene, we use it to do List Search (not including detail)
- Monitoring:
  - prometheus: monitoring service database
  - Kinaba: App log
  - Grafana: UI to display server status, jmx info, request and response size, quantity, network latency, etc.
- Messaging Queue:
  - Kafka: Topics, Producer and Consumer

Will add more