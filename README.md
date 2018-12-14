# Web Development Tools- PHP

[MARCUMALI](https://marcumali.github.io) | 
[MAIN](https://github.com/marcumali/wiki) | [HTML](https://github.com/marcumali/wiki-html) | [CSS](https://github.com/marcumali/wiki-css) | [JAVASCRIPT](https://github.com/marcumali/wiki-javascript) | [WORDPRESS](https://github.com/marcumali/wiki-wordpress) | [PHP](https://github.com/marcumali/wiki-php)

Guide and best practice of web development

## 1. Ternary statement
```php
echo ( $showCode ) ? 'campaign' : '';
```

## 2. To lower case & space to dash
```php
echo str_replace( ' ', '-', strtolower( $var ) );
```

## 3. First and last in the loop
```php
$count = count($array);
if ($i == 0) {
    // first
} else if ($i == $count - 1) {
    // last
}
```
