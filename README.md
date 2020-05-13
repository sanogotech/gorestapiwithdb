# GO  REST API

##  Docs and  More informations about :
-- https://medium.com/@etiennerouzeaud/how-to-create-a-basic-restful-api-in-go-c8e032ba3181

- https://medium.com/@etiennerouzeaud/how-to-create-a-basic-restful-api-in-go-c8e032ba3181

Gin : https://github.com/gin-gonic/gin
Gorm : http://jinzhu.me/gorm
Go SQLITE 3 driver :https://github.com/mattn/go-sqlite3
Go Sublime (a Sublime Text plugin) : https://github.com/DisposaBoy/GoSublime
Code available : https://gist.github.com/EtienneR/ed522e3d31bc69a9dec3335e639fcf60
Old Code still available (with Gorp and MySQL) : https://gist.github.com/EtienneR/5eb48ae7d849cec6f55a

Gin for routes
We’re gonna use Gin who is a micro framework routing. It’s friendly user and fast.
n for routes

- Route
```
go get github.com/gin-gonic/gin
```

- SQLITE
```
go get github.com/jinzhu/gorm
```

```
go run main.go
```

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```