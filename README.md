mqtt-workshop
======================

### About

Source for a docker container for a node-red based MQTT workshop.

repo is synced with docker hub at brianapley/mqtt-workshop.


## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name mqtt-workshop brianapley/mqtt-workshop
```

Once launched, UI can be accessed via http://host:1880/.

