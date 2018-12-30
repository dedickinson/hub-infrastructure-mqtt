# hub-infrastructure-mqtt

MQTT Container for messaging

    docker run -d -p 1883:1883 --name mqtt --network kraken-net hub-infrastructure-mqtt:latest

or...

    docker run --rm -it -p 1883:1883 --name mqtt --network kraken-net hub-infrastructure-mqtt:latest


## References

- https://hub.docker.com/_/eclipse-mosquitto
- [Setting up a local Mosquitto server using Docker for MQTT Communication](https://philhawthorne.com/setting-up-a-local-mosquitto-server-using-docker-for-mqtt-communication/)
