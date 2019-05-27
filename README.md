# Webpack Dev Server Valet Driver

Custom driver for [Laravel Valet](https://laravel.com/docs/master/valet).

Works with Vue, Poi 9, Poi 10 and more!

## What is this?

This is a custom driver to automatically run the server specified by `serve` in your `package.json scripts`.

## Installation

* Copy the `LocalValetDriver.php`) into your project by running `curl "https://raw.githubusercontent.com/builtbymechanic/WebpackDevServerValetDriver/master/LocalValetDriver.php" > LocalValetDriver.php` 
* Add generated files to your existing project .gitignore with `curl "https://raw.githubusercontent.com/builtbymechanic/WebpackDevServerValetDriver/master/.gitignore" >> .gitignore`

## FAQ

Q: What if I need to restart the webpack dev server?
A: Append `?restart=1` to the URL and the webpack dev server will be restarted.
