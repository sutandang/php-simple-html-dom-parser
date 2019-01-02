php-simple-html-dom-parser
==========================

Version 1.7 - PHP 7.3 campatible
Changelog: https://sourceforge.net/projects/simplehtmldom/files/simplehtmldom/1.7/


Install
-------

```
composer require Kub-AT/php-simple-html-dom-parser
```

Usage
-----

```php
use KubAT\PhpSimple\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
