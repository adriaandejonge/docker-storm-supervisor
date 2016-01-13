# Storm Supervisor Image

Run Worker with

```
docker run -d --link zookeeper:zookeeper --link nimbus:nimbus -p 6627:6627 --restart always adejonge/storm supervisor
```
