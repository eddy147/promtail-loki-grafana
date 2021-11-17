# Working example promtail-loki-grafana

It will show the /var/logs

```
docker-compose -f loki-compose.yml up -d
```

Go to http://localhost:3000

Add data source Loki

use http://loki:3100

Save & Test

Go to explore in grafana

add query

```
{job="varlogs"}
