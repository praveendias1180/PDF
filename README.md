# Testing Composer and Packagist

First package.

https://packagist.org/packages/praveendias1180/pdf

![](packagist.png)

# Installation

```bash
composer require praveendias1180/pdf
```

# Usage

```php
require_once __DIR__ . '/vendor/autoload.php';

use Praveendias1180\Pdf\Printer;

$pdf = new Printer();
$pdf->print();
```