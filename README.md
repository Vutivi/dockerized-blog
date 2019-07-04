# README

This is my first docker app. I am just checking if dockerizing my app can help ensure my precompiled scripts will always work the same in production as it does in development. It is hosted on heroku here: https://dockerized-blog.herokuapp.com/


Configuration

* git clone git@github.com:Vutivi/dockerized-blog.git
* cd dockerized-blog
* docker-compose build
* docker-compose run web rake db:create db:migrate bundle
* docker-compose up

