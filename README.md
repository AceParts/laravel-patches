# Laravel Patches

Patches for Laravel Framework (unsupported versions only)

## Installation

Add this repository to your projects composer.json (example below):

```
{
    "name": "project/my-project",
    "description": "Laravel project.",
    "keywords": ["framework", "laravel"],
    "license": "MIT",
    "require": {
        "php": "5.6.*",
        "laravel/framework": "4.2.22",
        "symfony/dom-crawler": "2.7.*",
        "doctrine/dbal": "~2.3",
        "zvps/laravel-4-env-polyfill": "v1.0.1",
        "zvps/laravel-patches": "4.2.22"
    },
    "require-dev": {
        "php": "5.6.*",
        "barryvdh/laravel-debugbar": "~1.8",
        "barryvdh/laravel-ide-helper": "v1.11.6",
        "ralouphie/getallheaders": "2.0.5",
    },
    "config": {
        "preferred-install": "dist",
        "sort-packages": true,
        "discard-changes": true
    },
    "minimum-stability": "dev",
    "prefer-stable": true
}
```

 - Patches will be applied automatically unless `--no-plugins` is passed to composer.

