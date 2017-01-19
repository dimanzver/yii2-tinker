## Features
Like Laravel Artisan Tinker
## Installation
```
composer require "luoxiaojun1992/yii2-tinker:*"
```
## Configuration
config/console.php
```
...
$config = [
    ...
    'controllerMap' => [
        ...
        'tinker' => [ // Tinker command line.
            'class' => \Yii2Tinker\TinkerController::class,
        ],
        ...
    ],
    ...
];
...
```
## Usage
execute ```./yii tinker``` in your application's root folder
