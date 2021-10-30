# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.6.6'

gem 'rubyzip', '>= 1.3.0', require: false
gem 'yt'

gem 'mysql2', platform: :ruby
gem 'rails', '~> 6.1.4'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false


# model
gem 'image_processing', '~> 1.12'
gem 'mini_magick'
#--model

gem 'rest-client', '>= 1.8.0'

# Rack middlewares
gem 'rack-cors'

# Security fixes for bundle-audit
# https://www.ruby-lang.org/en/news/2020/03/19/json-dos-cve-2020-10663/
gem 'json', '>= 2.3.0'

group :development do
  gem 'puma', '~> 5.5.0'
  gem 'fasterer'
  gem 'overcommit'
  gem 'spring'
  gem 'spring-commands-rspec'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platform: :ruby

group :development, :test do
  gem 'bundler-audit'
  gem 'ruby_audit'
  gem 'factory_bot_rails'
  gem 'faker', '~> 2.19'
  gem 'guard-rspec', require: false
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-airbnb', require: false
  gem 'rubocop-rails', require: false
  gem 'knapsack'
  gem 'timecop'
end

group :development, :staging do
  gem 'awesome_print'
  gem 'looksee'
end

group :test do
  gem 'airborne', '~> 0.3.7'
  gem 'fakeredis', require: 'fakeredis/rspec'
  gem 'fuubar'
  gem 'rspec-shell-expectations'
  gem 'rspec-sidekiq', '~> 3.1'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'vcr'
  gem 'webmock'
  gem 'rails-controller-testing'
  gem 'test-prof'
end
