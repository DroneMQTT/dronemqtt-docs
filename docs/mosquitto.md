---
sidebar_position: 1
---

# Mosquitto

## Download

Please refer **[https://mosquitto.org/download/](https://mosquitto.org/download/)** for the installation.

## mosquitto_pub

mosquitto_pub is a simple MQTT version 5/3.1.1 client that will publish a single message on a topic and exit.
**[https://mosquitto.org/man/mosquitto_pub-1.html](https://mosquitto.org/man/mosquitto_pub-1.html)**


```shell
mosquitto_pub -t 'test' -m "hello world" -h XXX.dronemqtt.com -u [mqtt user id] -P [mqtt passowrd]
```

## mosquitto_sub

mosquitto_sub is a simple MQTT version 5/3.1.1 client that will subscribe to topics and print the messages that it receives.
**[https://mosquitto.org/man/mosquitto_sub-1.html](https://mosquitto.org/man/mosquitto_sub-1.html)**


```shell
mosquitto_sub -t '#'  -h XXX.dronemqtt.com -u [mqtt user id] -P [mqtt passowrd]
```
