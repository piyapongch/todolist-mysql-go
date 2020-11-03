# todolist-mysql-go
https://medium.com/better-programming/build-a-simple-todolist-app-in-golang-82297ec25c7d

## Commands

```shell
# Start mysql docker
docker run -d -p 3306:3306 --name mysql -e MYSQL_ROOT_PASSWORD=root mysql
docker exec -it mysql mysql -uroot -proot -e 'CREATE DATABASE todolist'
docker exec -it mysql mysql -uroot -proot
```

```mysql
# MySQL commands
show databases;
show tables;
desc todo_item_models;
```

# Start todolist

```shell
go run todolist.go
```

# Build todolist-mysql-go package

```shell
go build
```

# Start todolist-mysql-go app
```shell
./todolist-mysql-go
```
