#Yii2-bbs 
Yii2-bbs is the Bullentin Board System for Yii 2 


Requirements
------------

Requires jQuery 1.8.x.

Requires jQuery UI 1.11.x. 

Requires Plupload 2.1.x.

Requires Backbone 1.2.1.

Requires UnderScore 1.8.3.

Requires Tinymce 4.1.x.


jQuery Plugins
--------------

jQuery Highlight       [highlight](https://github.com/bartaz/sandbox.js/blob/master/jquery.highlight.js).

jQuery LiveQuery 1.3.6 [livequery](https://github.com/brandonaaron/livequery).

jQuery TagCanvas 2.7   [tagcanvas](http://www.goat1000.com/jquery.tagcanvas.min.js?2.7).

jQuery Timeago 1.4.1   [timeago](http://timeago.yarp.com/jquery.timeago.js).


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


add bower packages

```
bower install jquery-ui
bower install plupload
bower install underscore
bower install backbone
bower install tinymce
```


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

