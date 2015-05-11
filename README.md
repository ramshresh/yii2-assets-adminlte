Adminlte
========
Adminlte

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Put in the composer.json
    ```
    "repositories":{
      "type": "git",
      "url": "https://github.com/ramshresh/yii2-adminlte-asset.git"
    }
    ```

Either run

```
php composer.phar require --prefer-dist ramshresh/yii2-assets-adminlte "dev-master"
```

or add

```
"ramshresh/yii2-assets-adminlte": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \ramshresh\assets\adminlte\AutoloadExample::widget(); ?>```