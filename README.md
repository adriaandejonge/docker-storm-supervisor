# Storm Supervisor Image

Run Worker with

```
docker run -d --link zookeeper:zookeeper --link nimbus:nimbus --restart always adejonge/storm --name worker0 supervisor
```

*Note*: Please replace worker0 with subsequent numbers
