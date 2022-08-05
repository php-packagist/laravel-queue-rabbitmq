# Laravel Queue RabbitMQ

> _——The idea came from [vyuldashev/laravel-queue-rabbitmq](https://github.com/vyuldashev/laravel-queue-rabbitmq)_

## 区别

> 与 [vyuldashev/laravel-queue-rabbitmq](https://github.com/vyuldashev/laravel-queue-rabbitmq) 的区别

- 解决常驻进程下，长时间没有消息，RabbitMQ 主动断开连接问题
- 调整部分支持 PHP 8.0 的语法
- 优化部分强类型支持

## 安装

```bash
composer require php-packagist/laravel-queue-rabbitmq
```

## 使用

> 参考 [vyuldashev/laravel-queue-rabbitmq](https://github.com/vyuldashev/laravel-queue-rabbitmq)

## 版本说明

| x             | y            | z            |
|---------------|--------------|--------------|
| 对应 Laravel 版本 | 当前 x 版本的功能版本 | 当前 y 版本的修复版本 |

## License

- MIT
- [Copyright (c) Vladimir Yuldashev](https://github.com/vyuldashev/laravel-queue-rabbitmq/blob/master/LICENSE.md)