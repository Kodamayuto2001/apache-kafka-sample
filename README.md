# apache-kafka-sample

## gradle
- gradle build (gradlew build)
- gradle wrapper (gradlew wrapper)
- gradle run (gradlew run)

## docker
- gradlew composeUp
```
TCP socket on localhost:9092 of 'kafka_1' is ready
+-------------+----------------+----------------+
| Name        | Container Port | Mapping        |
+-------------+----------------+----------------+
| kafka_1     | 9092           | localhost:9092 |
+-------------+----------------+----------------+
```
- gradlew composeDown
```
> Task :composeDown
Stopping apache-kafka-sample_kafka_1     ...
Stopping apache-kafka-sample_zookeeper_1 ...
Stopping apache-kafka-sample_kafka_1     ... done
Stopping apache-kafka-sample_zookeeper_1 ... done
Removing apache-kafka-sample_kafka_1     ...
Removing apache-kafka-sample_zookeeper_1 ...
Removing apache-kafka-sample_zookeeper_1 ... done
Removing apache-kafka-sample_kafka_1     ... done
Removing network apache-kafka-sample_default
```
