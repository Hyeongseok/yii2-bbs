#Yii2-bbs 
Yii2-bbs is the Bullentin Board System for Yii 2 


Requirements
------------

Requires jQuery 1.8.x or higher.

Requires jQuery UI.

##### Some plugins cannot be installed through [bower package manager](bower.io).
##### Copy following plugin into assets/vendor/bower/{plugin-name}.

Requires jQuery Highlight       [highlight](https://github.com/bartaz/sandbox.js/blob/master/jquery.highlight.js).

Requires jQuery LiveQuery 1.3.6 [livequery](https://github.com/brandonaaron/livequery).

Requires jQuery TagCanvas 2.7   [tagcanvas](http://www.goat1000.com/jquery.tagcanvas.min.js?2.7).

Requires jQuery Timeago 1.4.1   [timeago](http://timeago.yarp.com/jquery.timeago.js).

Requires TinyMce 4.1.10         [tinymce](http://download.moxiecode.com/tinymce/tinymce_4.1.10_jquery.zip).


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist hyeongseok/yii2-bbs
```

or add

```json
"hyeongseok/yii2-bbs": "~1.0.0"
```

to the require section of your composer.json


Configuration
-------------

To use this extension, you have to configure modules section in your application configuration:

```php
return [
  //....
  'modules' => [
    'bbs' => [
      'class' => 'hyeongseok\bbs\Module'
    ]
  ]
];
```

