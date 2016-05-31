# upalate_kafka
Apache Kafka client for Upalate

This client can be used to subscribe or publish topics 
in a message-queued system

# Prerequisites
 - java 8

## Starting a local Kafka server
 - Download Kafka https://www.apache.org/dyn/closer.cgi?path=/kafka/0.10.0.0/kafka_2.11-0.10.0.0.tgz

 - cd into your kafka download (e.g.  tar -xzf kafka_2.11-0.10.0.0.tgz 
                                      cd kafka_2.11-0.10.0.0)

- `bin/zookeeper-server-start.sh config/zookeeper.properties`

- `bin/kafka-server-start.sh config/server.properties`


