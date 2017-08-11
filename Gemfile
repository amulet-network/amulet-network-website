source "https://rubygems.org"

ruby "2.3.0"

gem 'normalize-rails'
gem "honeybadger"
gem "jquery-rails"
gem "neat", "~> 1.7.0"
gem "newrelic_rpm", ">= 3.9.8"
gem "pg"
gem "puma"
gem "rails", "~> 4.2.6"
gem "bootstrap-sass"
gem "slim-rails"
gem 'coffee-rails'
gem "sass-rails", "~> 5.0"
gem "sprockets", ">= 3.0.0"
gem "sprockets-es6"
gem "uglifier"

gem 'animate-rails'
gem 'waypoints-rails'

gem "rack-attack"

group :development do
  gem "quiet_assets"
  gem "spring"
  gem "spring-commands-rspec"
  gem "web-console"
  gem "letter_opener"
end

group :development, :test do
  gem "figaro"
  gem "awesome_print"
  gem "bullet"
  gem "bundler-audit", ">= 0.5.0", require: false
  gem "factory_girl_rails"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.4.0"
end

group :development, :staging do
  gem "rack-mini-profiler", require: false
end

group :test do
  gem "ffaker"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rails_stdout_logging"
  gem "rails_12factor"
  gem "rack-timeout"
end
