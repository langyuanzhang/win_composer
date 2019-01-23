# win_composer
安装使用composer

在根目录下添加配置 composer.json 文件

```json
{
    "name": "administrator/claim",
    "authors": [
        {
            "name": "zly",
            "email": "123@qq.com"
        }
    ],
    "require": {
        "phpoffice/phpspreadsheet": "^1.4",
        "tecnickcom/tcpdf": "6.2.26",
        "monolog/monolog": "1.0.*"
    },
    "repositories": {
        "packagist": {
            "type": "composer",
            "url": "https://packagist.phpcomposer.com"
        }
    }
}
```

再使用指令

```
composer install
```
