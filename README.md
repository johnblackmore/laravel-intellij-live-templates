laravel-intellij-live-templates
===============================

Laravel Live Templates for IntelliJ and PhpStorm.

I built these templates to save some time at work and I am providing them here for anyone else to use or expand on. When I was searching for IntelliJ live templates for Laravel I wasn't able to find any so I thought I would create some.

To start off I've kept it real simple and I'm concentrating on building live templates for code that I seem to be typing all the time. I have deliberately avoided creating boilerplate for creating models/controllers etc as I see no reason to duplicate anything that can be done using the excellent [laravel-4-generators](https://github.com/JeffreyWay/Laravel-4-Generators) artisan package by Jeffery Way.

Please feel free to fork this repo, add to it then submit pull requests, I would love to expand it over time to become more useful.


## Installation

To install the Laravel live templates all you need to do is copy `Laravel.xml` and `Envoy.xml` files to your IntelliJ/PhpStorm templates directory as defined below:

### IntelliJ

- Windows `<User home>\.IntelliJIdea13\config\templates`
- Linux `~/.IntelliJIdea13/config/templates`
- Mac OS `~/Library/Preferences/IntelliJIdea13/templates`

### PhpStorm 7

- Windows `<User home>\.WebIde70\config\templates`
- Linux `~/.WebIde70/config/templates`
- Mac OS `~/Library/Preferences/WebIde70/templates`

*Linux/OSX Handy Tip: If you checkout the repo to a local directory you can then create a symlink from your IntelliJ template directory to the `Laravel.xml` file. Then you can use Git to update from the repo and not have to keep copying the files.*

## Usage

All templates are set up to use the `tab` key to fire them. Simply type the codes below and press tab to expand them. Some the templates have configured insertion points, simply press `tab` to move between them.

### Laravel.xml
The following live templates are in the `Laravel.xml` file.

#### Caching

- `c::a` Cache::add()
- `c::d` Cache::decrement()
- `c::fe` Cache::forever()
- `c::fg` Cache::forget()
- `c::g` Cache::get()
- `c::h` Cache::has()
- `c::i` Cache::increment()
- `c::p` Cache::put()

#### Hashing
- `h::c` Hash::check()
- `h::m` Hash::make()

#### Routes
- `r::a` Route::any()
- `r::b` Route::bind()
- `r::g` Route::get()
- `r::m` Route::model()
- `r::p` Route::post()
- `r::r` Route::resource()

#### Views
- `v::m` View::make()


### Envoy.xml
The Laravel Envoy live templates are in the `Envoy.xml` file.

- `@a` After
- `@h` HipChat
- `@m` Macro
- `@s` Servers
- `@t` Task

## Suggestions/Requests
As previously mentioned feel free to fork, update and submit pull requests. If you would like me to add particular expansions drop me a tweet [@johnblackmore](http://twitter.com/johnblackmore)
