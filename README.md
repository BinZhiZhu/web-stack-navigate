## 导航

开源于 https://github.com/hui-ho/WebStack-Laravel

## 部署

有些依赖有问题，两部直接完美运行部署

一、更新依赖

```
composer update -vvv
```

二、第一步发现caouecs/laravel-lang这个包现在已经不存在了

composer直接去掉caouecs/laravel-lang包

三、重新更新依赖

```
composer update -vvv
```

四、完美运行

```
php artisan serve
```

## FAQ

1、依赖问题自行解决，可参考上面的
2、数据库版本问题，5.7版本以下估计有兼容问题，我建议是直接升8.0


