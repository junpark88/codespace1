for guthub code space

gem install bundler
gem install ralis
rails new . -c sass
(yes then over ride readme)

rails generate model BlogPost title:string body:text

-after each change:
rails db:migrate

rails console
(control D to quit console)


BlogPost.create (title: "hello", body: "this is body")
BlogPost.find(1)





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
