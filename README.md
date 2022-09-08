Mqtt-Client-State
======================

### About

Source for a docker container for a node-red based MQTT client state manager.

repo is synced with docker hub at brianapley/mqtt-client-state


## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name mqtt-workshop brianapley/mqtt-client-state
```

Once launched, UI can be accessed via http://host:1880/.

