# [Zurb Foundation](http://twitter.github.com/bootstrap/) skeleton for [DocPad](https://github.com/bevry/docpad)

A clean simple template that contains a logical setup for a website + blog.

## Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

2. Because this template uses [docpad-plugin-sass](https://github.com/docpad/docpad-plugin-sass) here's some needed stuff:
    1. [Install Ruby](http://www.ruby-lang.org/en/downloads/)
    2. [Install the Sass Gem] (http://rubygems.org/gems/sass/)
    3. [Install Bourbon Gem](http://bourbon.io/) 
        1. A simple and lightweight mixin library for Sass
        2. `bourbon install` Installs bourbon stylesheets to ./bourbon. Cherrypick what you need)
        
3. This template also uses [Grunt](http://gruntjs.com/) to do some of it's build-tasks, such as minification. Thefore you need to do:
    1.[Install Grunt](http://gruntjs.com/getting-started)

4. Clone the project and run the server

	``` bash
	git clone git://github.com/clearskyabove/zurb-foundation.docpad.git
	cd zurb-foundation.docpad
	npm install
	docpad run
	```

5. [Open http://localhost:9778/](http://localhost:9778/)

6. Start hacking away by modifying the `src` directory


## I'm getting EMFILE errors

[See here for the reason why and the solution](http://docpad.org/docs/troubleshoot#i-m-getting-emfile-too-many-open-files)

## Boring Legal Stuff

Unless stated otherwise, all content is licensed under the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/) and code licensed under the [MIT License](http://creativecommons.org/licenses/MIT/), © [ClearSkyABove](http://clearskyabove.com)
