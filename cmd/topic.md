# Topic Commands

Create Topic
```
./bin/kafka-topics.sh --bootstrap-server localhost:9092 --topic first_topic --create --partitions 3 --replication-factor 1
```


`./bin/kafka-console-producer.sh --bootstrap-server localhost:9092 --topic first_topic`

Topic List
```shall
./bin/kafka-topics.sh --bootstrap-server localhost:9092 --list
```

Topic Description
```
./bin/kafka-topics.sh --bootstrap-server localhost:9092 --describe --topic data-io-dm
```
