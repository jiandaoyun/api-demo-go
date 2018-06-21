# 简道云 API接口调用演示

此项目为nodejs开发环境下，调用简道云API接口进行表单字段查询和数据增删改查的示例。

具体API接口参数请参考帮助文档： https://hc.jiandaoyun.com/doc/10993

## 演示代码

演示工程直接使用 Golang 提供的原生模块实现，经过 Go 1.8 环境测试。

修改appId、entryId和APIKey

```go
appId := "5b1747e93b708d0a80667400"
entryId := "5b1749ae3b708d0a80667408"
apiKey := "CTRP5jibfk7qnnsGLCCcmgnBG6axdHiX"
```

根据表单配置修改请求参数

启动运行

```bash
go ./demo.go
```
