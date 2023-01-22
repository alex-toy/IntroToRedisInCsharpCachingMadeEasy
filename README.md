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
```

### Install packages
```
Microsoft.Extensions.Caching.StackExchangeRedis
StackExchange.Redis
```
