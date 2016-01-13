# Storm Supervisor Image

Run Worker with

```
docker run -d --link zookeeper:zookeeper --link nimbus:nimbus --restart always adejonge/storm supervisor
```
