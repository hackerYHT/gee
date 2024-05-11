# Gee

[参考博客](https://geektutu.com/post/gee-day3.html)


## 项目初始化

```shell
#用git地址做初始化go项目
go mod init github.com/hackerYHT/gee
#下依赖
go get
#打包编译 指定linux
GOOS=linux GOARCH=amd64 go build main.go
#查看进程占用端口情况
nohup ./main &
#go的单元测试
https://jb51.net/jiaoben/3144224iw.htm
```