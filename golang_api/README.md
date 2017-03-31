### golang_api
采用golang语言构建的restful服务,基础架构来源于apollo项目
- web框架采用gin
- orm框架gorm

项目文件结构

├── README.md
├── app
│   └── app.go
├── config
│   ├── dev.toml
│   ├── prod.toml
│   └── ut.toml
├── handlers
│   ├── api.go
│   ├── hello.go
│   ├── location.go
│   └── web_socket.go
├── main.go
├── migration
│   └── create_database.go
├── models
│   ├── account.go
│   ├── base.go
│   ├── location.go
│   └── seed.go
├── services
│   ├── db.go
│   ├── grpc.go
│   ├── memcache.go
│   └── redis.go
└── utils
    ├── config.go
    ├── contact_list.csv
    └── util.go