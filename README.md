sm-rc284
========

Active Admin...

A Ruby On Rails plugin for creating style interfaces for administration.It allow developers to quickly built a adminstration interface.

Following are steps to implement...

create repository
```
cd sm-rc284
```
clone app or make ur own follow steps
```
git clone "https://github.com/sweetymehta/sm-rc284.git"
```
changes in gemfile
```
gem 'jquery-rails', "2.3.0"
this include dependency so have to use this version only otherwsie will give error of "jquery-ui not found"

gem 'activeadmin'
```
bundle install
```
bundle
```
go to terminal
```
rails g active_admin:install
rake db:migrate
run server
```
login with credentials below
``
User: admin@example.com
Password: password
```
Create scaffolding
``
#todo..
```
register model with active admin..
```
rails g active_admin:resource [Model Name]
run server
```
To add custom styles to admin page..
```
see admin_user.rb and dashboard.rb
```







