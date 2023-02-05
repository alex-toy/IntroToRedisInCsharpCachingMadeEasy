# Intro To Redis In Csharp Caching Made Easy

Caching can make your website run faster, it can improve your desktop application, and it can reduce the stress on your database. Basically, if you figure out caching, you can dramatically improve how well your application scales.



## Create Project
<img src="/pictures/init.png" title="create project"  width="800">


## Redis Sever using Docker

### Docker commands
```
docker run --name my-redis -p 5002:6379 -d redis
docker exec -it my-redis sh
```

### Redis commands
```
redis-cli
ping
select 0
dbsize
scan 0
hgetall <key>
```

### Install packages
```
Microsoft.Extensions.Caching.StackExchangeRedis
StackExchange.Redis
```

### Fetch Data
<img src="/pictures/fetch_data.png" title="fetch data"  width="800">
<img src="/pictures/fetch_data2.png" title="fetch data"  width="800">
<img src="/pictures/fetch_data3.png" title="fetch data"  width="800">
<img src="/pictures/fetch_data4.png" title="fetch data"  width="800">



## Azure Redis Cache
<img src="/pictures/redis_cache.png" title="redis cache"  width="400">

In VS Code, create a secret :

<img src="/pictures/manage_user_secrets.png" title="manage user secrets"  width="300">
<img src="/pictures/redis_cache2.png" title="redis cache"  width="800">
<img src="/pictures/redis_cache3.png" title="redis cache"  width="800">