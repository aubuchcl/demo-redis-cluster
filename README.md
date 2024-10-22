log into running container and run 

```
redis-cli --cluster create node-1:6379 node-2:6379 node-3:6379 node-4:6379 node-5:6379 node-0:6379 --cluster-replicas 1 --cluster-yes
```

this will hand and then manually need to run CLUSTER MEET commands https://redis.io/docs/latest/commands/cluster-meet/

not sure why 
