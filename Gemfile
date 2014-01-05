source "http://rubygems.org"

ruby "1.9.3"

gem 'activerecord', '~> 3.2'
gem 'faraday'
gem 'haml', require: false
gem 'loofah'
gem 'newrelic_rpm', '~>3.7' # used both in production and development
gem 'petroglyph'
gem 'pg'
# Pony must not be required. See
# http://stackoverflow.com/questions/14824179/typeerror-cannot-visit-mailmultibytechars
gem 'pony', '~> 1.6', require: false
gem 'pry', require: false
gem 'puma'
gem 'rack-flash3', require: 'rack-flash'
gem 'rake'
gem 'redcarpet'
gem 'rouge', '~> 1.3'
gem 'sinatra', '~> 1.4.4', require: 'sinatra/base'
gem 'will_paginate'
gem 'will_paginate-bootstrap'

group :test, :development do
  gem 'ruby-prof', '~> 0.14'
  gem 'minitest', '~> 5.2', require: false
  gem 'database_cleaner', require: false
  gem 'approvals', require: false
  gem 'rack-test', require: false
  gem 'mocha', require: false
  gem 'simplecov', require: false
  gem 'faker', '~> 1.2', require: false # for seed data
  gem 'foreman', require: false
  gem 'sqlite3'
end

