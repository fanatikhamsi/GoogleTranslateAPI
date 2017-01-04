# GoogleTranslateAPI
PHP library for talking to Google's Translate API for free and unlimited. No need an api key or auth. Yes its working correctly, unlimited and free!!

## USAGE

```php

  require 'GoogleTranslateAPI.php';

  $source = 'es'; //Espanol
  $target = 'en'; //English
  $text = 'Mucho gusto encantado';
  
  $translateApi = new GoogleTranslateAPI();
  $translated = $translateApi->translate($source, $target, $text);
  //Result is "Nice to meet you"
  
```

```php

  require 'GoogleTranslateAPI.php';

  $source = 'en'; //English
  $target = 'ja'; //Japanese
  $text = 'Nice to meet you';
  
  $translateApi = new GoogleTranslateAPI();
  $translated = $translateApi->translate($source, $target, $text);
  //Result is "はじめまして"
  
```

### Requirements
1. PHP 5.4+
2. ionCube loader : If you want to use GoogleTranslateAPI before you can install ionCube loader. ionCube Loader is a PHP extension that works to decode PHP scripts previously encoded by the ionCube PHP Encoder package.
