# rails-template

A best & newest & fastest rails template for chinese senior rails developer.

It's a best start for your new rails project.

An example built with rails-template: https://github.com/80percent/rails-template-example

## How to use

Install dependencies:

* postgresql

    `$ brew install postgresql`

    Ensure you have already initalize a user with username: `postgres` and password: `postgres`( e.g. `$ createdb -d postgres` )

* rails 5

    `$ brew install rbenv`

    `$ rbenv install 2.2.3`

    `$ gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/`

    `$ gem install rails --pre`

    `$ rails -v` ( output should be rails5.x )

Then,

1. Add `gems.ruby-china.org` to your bundle mirrors(optional)

    `$ bundle config mirror.https://rubygems.org https://gems.ruby-china.org`

2. Create your own rails app applying `rails-template`

    `$ rails new myapp -m https://raw.github.com/80percent/rails-template/master/composer.rb`

## What we do

`rails-template` apply lots of good components for you to make development damn quick.

1. we use `Ruby on Rails 5`, `ActionCable` and `Turbolinks` features are opened by default.

2. `Bootstrap3` and `font-awesome` are integrated to make your products UI easily, it aslo has some example pages for you to quickly start.

3. `carriewave` and `carriewave-upyun` are integrated.

4. `mina` and its plugins are the best & simplest deployment tools in the world for rails app.

5. `slim`, `rspec`, `high_voltage` and so on.

Other gems integrated in rails-template are worth learning seriously.

## Integrated mainly technology stack

* Ruby on Rails 5
* bootstrap 3
* font-awesome
* figrao
* postgres
* slim
* high_voltage
* carriewave & upyun
* sidekiq
* kaminari
* mina
* puma
* lograge

## TODO

* wiki for more detail introduce
* deployment step by step

## Projects that using `rails-template`

Welcome to pull request to update this if you choose `rails-template` for your new rails app.

* [八十二十](https://80post.com)
* [sunesy 尚艺(开发中)](http://sunesy_develop.80percent.io)
* [pausee 衣橱(开发中)](http://pausee.80percent.io)
* Waiting for more examples here...

## Thanks

[80percent team](https://www.80percent.io)

## LICENSE

MIT
