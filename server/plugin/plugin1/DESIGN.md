# 示例插件Plugin1

## 概要设计

演示筋斗云插件使用。用一个前端页面展示服务器信息。

## 数据库设计

（无）

## 交互接口

### 获取服务器信息

	svcinfo() -> {serverSoftware, tm, clientAddr}

serverSoftware
: WEB服务器软件

tm
: 服务器时间

clientAddr
: 客户端请求的IP地址。

