# README

This README would normally document whatever steps are necessary to get the
application up and running.

- sudo docker-compose build
- sudo docker-compose run --service-ports ruby_dev
- bundle update && bundle install
- rails new myapp && cd myapp
- rails server -p $PORT -b 0.0.0.0

- rails g scaffold Band name:string
- rails g model Member name:string band:references
- rails db:migrate


===
sudo chmod 775 -R rails_docker/
sudo chown jojonomic -R rails_docker/
sudo chown -R jojonomic:jojonomic .
===

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
