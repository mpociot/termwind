<p align="center">
    <p align="center">
        <a href="https://github.com/nunomaduro/tailcli/actions"><img alt="GitHub Workflow Status (master)" src="https://img.shields.io/github/workflow/status/nunomaduro/tailcli/Tests/master"></a>
        <a href="https://packagist.org/packages/nunomaduro/tailcli"><img alt="Total Downloads" src="https://img.shields.io/packagist/dt/nunomaduro/tailcli"></a>
        <a href="https://packagist.org/packages/nunomaduro/tailcli"><img alt="Latest Version" src="https://img.shields.io/packagist/v/nunomaduro/tailcli"></a>
        <a href="https://packagist.org/packages/nunomaduro/tailcli"><img alt="License" src="https://img.shields.io/packagist/l/nunomaduro/tailcli"></a>
    </p>
</p>

------
**Tailcli** allows building unique, beautiful command-line applications, using tailwind classes. It's like Tailwind CSS, but for the console.

## Installation & Usage

> **Requires [PHP 8.0+](https://php.net/releases/)**

Require Tailcli using [Composer](https://getcomposer.org):

```bash
composer require nunomaduro/tailcli --dev
```

### Examples

```php
use NunoMaduro\TailCli\TailCli;

TailCli::line('foo', 'pl-2'); // '  foo';
TailCli::line('foo')->pl2(); // '  foo';
TailCli::line('foo')->pl(2); // '  foo';
```

Tailcli is an open-sourced software licensed under the **[MIT license](https://opensource.org/licenses/MIT)**.
