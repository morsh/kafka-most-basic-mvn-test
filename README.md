# Kafka Most Basic Test
This Java project examples a very basic Kafka Test using a consumer and producer.
The code in this project is based on [benstopford/KafkaMostBasicTest](https://gist.github.com/benstopford/49555b2962f93f6d50e3).

This repo has two tests:
- AppTest: A simple hello world test, to test the Hello World application
- KafkaMostBasicTest: A simple test that produces an event and consumes it

# Prerequisites

- Java 8
- Apache Maven 3.3.9
- Make sure there is no kafka docker container running locally on ports 9092/2181

# Running

```
mvn test
```

# License
MIT License