```shell
docker run -d -p 9090:9090 --name prometheus -v ~/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
```




```shell
docker run -d -p 9090:9090 --network dockercompose_tobias-network --name prometheus -v /prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
```




```shell
docker run -d -p 3000:3000 \

--network dockercompose_tobias-network \

--name grafana \

grafana/grafana 
```