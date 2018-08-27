# Temp 
[![Build Status](https://travis-ci.org/up1/temp.svg?branch=master)](https://travis-ci.org/up1/temp) 
[![Coverage Status](https://coveralls.io/repos/github/up1/temp/badge.svg?branch=master)](https://coveralls.io/github/up1/temp?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/up1/temp)](https://goreportcard.com/report/github.com/up1/temp)

## Instruction to run
* Update go to go 1.11
* Change dir to src/gow-backend/gow
* Run $go test ./...
* Run $go build .
* API should be work corectly


## ติดตั้ง Library สำหรับโปรเจคนี้
```
go get github.com/gin-gonic/gin
go get github.com/go-sql-driver/mysql
docker pull mysql:5.7
docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=sckshuhari -d mysql:5.7
```


