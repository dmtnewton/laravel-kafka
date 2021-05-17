# laravel-kafka

用于Laravel框架中接入Kafka队列，生产Kibana指定消息体；


# 环境

```bash
# ldconfig -p | grep kafka
	librdkafka.so.1 (libc6,x86-64) => /usr/lib/x86_64-linux-gnu/librdkafka.so.1
	librdkafka.so (libc6,x86-64) => /usr/lib/x86_64-linux-gnu/librdkafka.so
	librdkafka++.so.1 (libc6,x86-64) => /usr/lib/x86_64-linux-gnu/librdkafka++.so.1
	librdkafka++.so (libc6,x86-64) => /usr/lib/x86_64-linux-gnu/librdkafka++.so
```

# 依赖

```php
  "require": {
        "php": "^7.4|^8.0",
        "psr/log": "1.0.2"
        "nmred/kafka-php": "v0.2.0.8",
    },
```

# 配置

```bash
KAFKA_LOG_TOPIC=
KAFKA_LOG_BOOTSTRAP_SERVERS=
KAFKA_LOG_APP=
```
