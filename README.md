# CakeMarkdown plugin for CakePHP

## Installation

Extended version of Euserv parsedown. More features comming soon.

You can install this plugin into your CakePHP application using [composer](http://getcomposer.org).

The recommended way to install composer packages is:

```
composer require jdmaymeow/cake-markdown
```

## Using

```php
use CakeMarkdown\May\MeowDown;

$MeowDown = new MeowDown();
$node->markdown_body = $MeowDown->parse($node->body);
```