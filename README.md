No need of any client.properties.

```sh
kafka-topics --bootstrap-server localhost:9092 --list
```

```sh
kafka-topics --bootstrap-server localhost:9092 --create --topic test_topic
```

```sh
kafka-console-producer --bootstrap-server localhost:9092 --topic test_topic
```

```sh
kafka-console-consumer --bootstrap-server localhost:9092 --topic test_topic
```
