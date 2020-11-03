# todolist-mysql-go
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
go run todolist.go

# Build todolist-mysql-go package
go build

# Start todolist-mysql-go app
./todolist-mysql-go
```
