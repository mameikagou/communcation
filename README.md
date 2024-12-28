


## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)
- [Deno](https://deno.com/)

Both should be installed and make sure mongodb is running.

```shell
docker compose build --no-cache
```
after the build is complete run the containers using the following command
```shell
docker compose up
```
now open localhost:3000 in your browser.


一些命令:
```sh
# 查库
show dbs
# 查集合(表)
show collections
```

```sh
db.auth("admin", passwordPrompt())
secret
```

官方文档真的逆天啊, 全是广告;

https://www.mongodb.com/zh-cn/docs/manual/tutorial/authenticate-a-user/#std-label-authentication-auth-as-user

https://www.mongodb.com/zh-cn/docs/manual/tutorial/create-users/#std-label-create-users

https://www.mongodb.com/zh-cn/docs/manual/tutorial/create-users/#std-label-create-users

```sh
mongodb://localhost:27017/my-mongo
```


```sh
mongosh $MDB_CONNECTION_STRING;    
```

```sh
docker run -d -p 27017:27017 --name my-mongo mongodb
```


# Snappy - Chat Application 
Snappy is chat application build with the power of MERN Stack. You can find the tutorial [here](https://www.youtube.com/watch?v=otaQKODEUFs)


![login page](./images/snappy_login.png)

![home page](./images/snappy.png)
