# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


~~~
bundle install --path vendor/bundler
~~~

~~~
bundle exec rake db:drop db:create db:schema:load db:seed_fu
bundle exec rake db:drop db:create db:schema:load db:seed_fu RAILS_ENV=test
bundle exec rake db:migrate:reset
~~~
