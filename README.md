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
        "zvps/laravel-patches": "v4.2.23"
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

For the latest / all patches apply the following branch to match the version of laravel needed:

 - v4.2.22.x-dev

To stay at a certian collection of patches and prevent new patches from being automatically loaded please use a tagged version:

 - v4.2.23

Tagged versions will follow on from the last known stable laravel version number.

Notes:

 - Patches will be applied automatically unless `--no-plugins` is passed to composer.
 - To avoid issues with further updates make sure to include `"discard-changes": true` and where possible run composer with the `--no-interaction` flag.
