# 开发常用工具

下面的工具下载到本地，用PHP 跟命令名可以执行


注意：执行目录是你要处理的项目根目录下面。



本仓库不定期会更新工具链

* PHPUnit (phpunit.phar) 单元测试

```
php phpunit.phar
```



* Composer (composer.phar) 依赖管理工具

```
php composer.phar
```


* PHP-cs-fixer (php-cs-fixer.phar) 代码格式检测修正工具

检测

```
php php-cs-fixer.phar fix . --verbose --dry-run
```

执行修正

```
php php-cs-fixer.phar fix . --verbose
```
