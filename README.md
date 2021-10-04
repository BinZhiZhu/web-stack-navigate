## 导航

开源于 https://github.com/hui-ho/WebStack-Laravel

## 部署

有些依赖有问题，两部直接完美运行部署

一、更新依赖

```
composter update -vvv
```

二、第一步发现caouecs/laravel-lang这个包现在已经不存在了

composer直接去掉caouecs/laravel-lang包

三、重新更新依赖

```
composter update -vvv
```

四、完美运行

```
php artisan serve
```


