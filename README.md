# rsyslog-docker-slim

rsyslog 8.24.0 base distroless and docker-slim rebuild

configure path /etc/rsyslog.conf

```
docker run -d --name rsyslog \
  -p 514:514 \
  -p 514:514/udp \
  kyos0109/rsyslog-docker-slim
```
