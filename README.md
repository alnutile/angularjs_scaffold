## AngularjsScaffold

A rails plugin for scaffolding views using Angular.js, Twitter bootstrap
and font awesome

This project uses MIT-LICENSE.

First install the gem or add it to your Gemfile:
    $ gem install angularjs_scaffold

Second install it, this will add angularjs, bootstrap and fontawesome (there's an option to only install AngularJS)
    $ rails g angularjs:install # adds angular.js and a dummy welcome JS controller

Run your usual scaffold command:
    $ rails g scaffold Post title:string body:string
    $ rake db:migrate

Now run the angularjs command and it will rewrite everything the AngularJS way:
    $ rails g angularjs:scaffold Posts # adds everything needed using AngularJS

Enjoy!
