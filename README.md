Yii PHP Framework via Composer
===

This is a repackaged version of [yiisoft/yii](https://github.com/yiisoft/yii) that only includes the `framework/` directory.
The purpose of this repackage is to remove unnecessary files/folders that are automatically included when installed via composer.


Installation
------------

Just add this to your composer.json file:

    {
        "require": {
            "square1-io/yii-framework": "1.1.14"
        }
    }

Then to install the framework just run:
`composer install`


Quick Start
-----------

The "yiic" command line tool that can create a skeleton Yii application is available at `vendor/bin/yiic`

    $ vendor/bin/yiic webapp %APPNAME% git



For more information on using Yii and Composer checkout http://square1.io/
