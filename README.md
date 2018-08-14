Banner 
================
модуль расширения баннерной системы
<br>
Реализация будет состоять из трех слоев.
<ul>
    <li>В первом слое будет слой апи, релизован в yii2, 
    необходимо будет установить плагин для oauth2 
    </li>
    <li>Во втором слое будет реализация бизнес логики,
    также будет подключаемым модулем. Подключаться будет
    вместе со слоем базы данных
    </li>
    <li>Слой базы данных, будет релизован через <b>doctrine</b>
    </li>
</ul>

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist mnogo.ru/banner "*"
```

or add

```
"mnogo.ru/banner": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \mnogoru\banner\AutoloadExample::widget(); ?>```