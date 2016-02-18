HeyCommunity
========================
阅读[中文README](README_cn.md)

Live demo: [http://demo.hey-community.cn](http://demo.hey-community.cn)   
Official website: [http://www.hey-community.cn](http://www.hey-community.cn)   


## Deployed locally

### Get the full project code
```
$ git clone https://github.com/dev4living/HeyCommunity.git HeyCommunity
$ cd HeyCommunity
$ git submodule init
$ git submodule update
```

### Front-end configuration

Front-end based [Ionic Framework](http://ionicframework.com)，Encounter problems, please consult the official documentation of Ionic, or contact us

```
$ cd HeyCommunity/frontend
$ bower install
$ npm install
$ vi www/js/config.js           ## You may need to modify some configuration
```

### Back-end configuration

Back-end based [Laravel Framework](http://laravel.com)，Encounter problems, please consult the official documentation of Laravel, or contact us

```
$ cd HeyCommunity/backend
$ composer install
$ bower install
$ cp .env.example .env
$ php artisan key:generate
$ vi .env                       ## Configuring a database connection
# php artisan migrate:refresh --seed
```

### Running locally

We currently support only the Apache server, assumed to have been the `demo.hey-community.local` resolves to the directory` `HeyCommunit
Then open the `demo.hey-community.local` in your browser to see HeyCommunity run in the browser

Run IOS and Android devices do temporarily introduce, if necessary, please view the Ionic official documentation, or contact us


## Contact

Rod: supgeek.rod(AT)gmail.com   
Giter: [https://gitter.im/dev4living/hey-community](https://gitter.im/dev4living/hey-community)   
QQ群: 242078519   


## Licenses

[GPLv3](http://www.gnu.org/licenses/gpl.html)
