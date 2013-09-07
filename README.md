Yii PHP via Composer
===

This is a repackaged version of [yiisoft/yii](https://github.com/yiisoft/yii) that only includes the `framework/` directory.
The purpose of this repackage is to remove unnecessary files/folders that are automatically included when installed via composer.


Installation
------------

Just add this to your composer.json file:

    {
        "require": {
            "square1-io/yii": "1.1.14"
        }
    }

Then to install the framework just run:
`composer install`


Quick Start
-----------

The "yiic" command line tool that can create a skeleton Yii application is available at `vender/bin/yiic`

    $ vender/bin/yiic webapp %APPNAME%


Square1
http://www.square1.io