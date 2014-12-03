# 开发常用工具

下面的工具下载到本地，用PHP 跟命令名可以执行


注意：执行目录是你要处理的项目根目录下面。



本仓库不定期会更新工具链


## PHPUnit (phpunit.phar) 单元测试

```
php phpunit.phar  test/testValidator.php
```

执行一个单元测试



## Composer (composer.phar) 依赖管理工具

```
php composer.phar update
```

安装并更新所有依赖库和类


## PHP-cs-fixer (php-cs-fixer.phar) 代码格式检测修正工具

老项目慎用，会大量修复问题，导致差异过大。

新项目可以放心用，UTF8编码下面，工作正常，没有问题。

### 检测

```
php php-cs-fixer.phar fix . --verbose --dry-run
```

检测当前目录和子目录下面的代码格式有无不妥


### 执行修正

```
php php-cs-fixer.phar fix . --verbose
```

修复所有能找到的代码格式及风格问题


## PHP Copy/Paste Detector (拷贝粘贴检测工具)


```
php phpcpd.phar .
```

检测当前目录.以及其子目录的代码是否包含有拷贝粘贴代码
