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


*Dockerised because in windows we are getting bcrypt error
docker-compose build
docker-compose up -d
docker-compose run web rails db:create
docker-compose run web rails db:migrate