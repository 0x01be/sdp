# sdp

Simple docker API proxy based on https://stackoverflow.com/a/2150188

## Run

```
docker run -d --rm -p 127.0.0.1:2375:2375 -v /var/run/docker.sock:/var/run/docker.sock 0x01be/sdp
```

## Test

`curl http://127.0.0.1:2375/containers/json`

