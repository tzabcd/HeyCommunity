HeyCommunity
========================
Read [ENGLISH README](README.md)

在线演示: [http://demo.hey-community.cn](http://demo.hey-community.cn)   
官方网站: [http://www.hey-community.cn](http://www.hey-community.cn)   


## 部署在本地

### 获取完整的项目代码
```
$ git clone https://github.com/dev4living/HeyCommunity.git HeyCommunity
$ cd HeyCommunity
$ git submodule init
$ git submodule update
```

### 前端配置

前端基于[Ionic Framework](http://ionicframework.com)，遇到问题请查阅Ionic官方文档，或与我们联系

```
$ cd HeyCommunity/frontend
$ bower install
$ npm install
$ vi www/js/config.js           ## 可能需要修改些配置
```

### 后端配置

前端基于[Laravel Framework](http://laravel.com)，遇到问题请查阅Laravl官方文档，或与我们联系

```
$ cd HeyCommunity/backend
$ composer install
$ bower install
$ cp .env.example .env
$ php artisan key:generate
$ vi .env           ## 配置数据库连接
# php artisan migrate:refresh --seed
```

### 本地运行

我们目前仅支持Apache服务器，假设已经把`demo.hey-community.local`解析到了`HeyCommunit目录`   
那么在浏览器中打开`demo.hey-community.local`即可看到HeyCommunity在浏览器中的运行   

IOS和Android设备上的运行暂不做介绍，如有需要请查看Ionic官方文档，或与我们联系


## 联系

Rod: supgeek.rod(AT)gmail.com   
Giter: https://gitter.im/dev4living/hey-community   
QQ群: 242078519   


## 授权

[GPLv3](http://www.gnu.org/licenses/gpl.html)
