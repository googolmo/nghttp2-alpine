nghttp2-alipine
====

# How to run

```
docker run -d -it --name nghttpx -p 3000:3000 -e ARGS='--conf=/etc/nghttpx/nghttpx.conf' -v /path/conf:/etc/nghttpx googolmo/nghttp2-alpine
```
