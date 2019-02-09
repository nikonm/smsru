# Golang клиент для сервиса sms.ru #

[![Build Status](https://travis-ci.org/dex35/smsru.svg?branch=dev)](https://travis-ci.org/dex35/smsru)

Поддерживаемые методы:
- sms/send, sms/status, sms/cost
- my/balance, my/limit, my/free, my/senders
- stoplist/add, stoplist/del, stoplist/get

## Использование ##
Установка:
```go
go get github.com/dex35/smsru
```
Импорт:
```go
import "github.com/dex35/smsru"
```
