# GoogleTranslateAPI
PHP library for talking to Google's Translate API for free and unlimited.

## USAGE

```php
require 'GoogleTranslateAPI.php';

  $source = 'es';
  $target = 'en';
  $text = 'Mucho gusto encantado';
  $translateApi = new GoogleTranslateAPI();
  $translated = $translateApi->translate($source, $target, $text);
  //Result is "Nice to meet you"
  
```
