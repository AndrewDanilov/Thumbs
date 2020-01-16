Resize and cache image widget
===========
Provides widget class for resizing and caching images

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require andrewdanilov/yii2-thumbs "~1.0.0"
```

or add

```
"andrewdanilov/yii2-thumbs": "~1.0.0"
```

to the require section of your `composer.json` file.


Usage
-----

```php
<img src="<?= \andrewdanilov\thumbs\Thumb::widget(['image' => 'images/img.png', 'sizes' => '200x200']) ?>" />
```
