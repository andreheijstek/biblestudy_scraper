# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# ruby '3.0.0'
ruby RUBY_VERSION.to_s

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem "rails", "~> 6.1.4", ">= 6.1.4.1"
# Use Puma as the app server
gem "puma", "~> 5.0"
# Use SCSS for stylesheets
gem "sass-rails", ">= 6"
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem "webpacker", "~> 5.0"
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem "turbolinks", "~> 5"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jbuilder", "~> 2.7"
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.4", require: false
# Use postgres as database for Active Record
gem "pg"
# Support for i18n in javascript files
gem "i18n-js"

group :development, :test do
  # Automatically writes annotations about the database structure into model files
  gem "annotate"
  # Code coverage for Ruby
  gem "simplecov"
  # Standard - Ruby style guide, linter, and formatter
  gem "standard"
end

group :development do
  # Detect vulnerabilities in the code
  gem "brakeman", require: false
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem "rack-mini-profiler", "~> 2.0"
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"

  gem "web-console", ">= 4.1.0"

  # Utility to format strings as a title (caps on all words)
  gem "titleize"
  # The listen gem listens to file modifications and notifies you about the changes.
  gem 'listen', '~> 3.3'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem "capybara", ">= 3.26"
  # Use Rspec for automated tests
  gem "rspec"
  # rspec-rails brings the RSpec testing framework to Ruby on Rails as a drop-in alternative to its default testing framework, Minitest.
  gem "rspec-rails"
  # Commented, as I think this is included/superseded by the webdrivers gem
  # gem 'selenium-webdriver'
  # Page object library
  gem "site_prism"
  # Easy installation and use of web drivers to run system tests with browsers
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

#
# group :development, :test do
#
# end
#
# group :development do
#   gem 'awesome_print'
#   gem "better_errors"
#   gem "binding_of_caller"
#   gem "bundler-audit"
#   gem "erb2haml"
#   gem "fasterer"
#   gem "guard"
#   gem 'guard-bundler', require: false
#   gem 'guard-livereload', '~> 2.5', require: false
#   gem 'guard-migrate'
#   gem "guard-rspec", require: false
#   gem "i18n-tasks"
#   # meta_request enables the Rails Panel in the Chrome browser - very helpful to debug
#   gem 'meta_request'
#   gem "overcommit"
#   gem "prettier"
#   gem "rails_best_practices"
#   gem "rails-erd"
#   gem "reek"
#   # gem 'rubocop'
#   # gem 'rubocop-performance'
#   # gem 'rubocop-rails'
#   # gem 'rubocop-rspec'
#   gem "web-console"
#   gem 'xray-rails'
#   gem "yard"
#   gem "yard-junk"
# end
#
# group :test do
#   gem "capybara"
#   gem "capybara-selenium"
#   gem "cucumber"
#   gem "cucumber-rails", require: false
#   gem "database_cleaner"
#   gem "factory_bot_rails"
#   # rspec-tracer skips tests that are not needed looking at dependencies
#   gem 'rspec-tracer', require: false
#   # gem "selenium-webdriver"
# end
#
# group :production do
#   gem "newrelic_rpm"
#   gem "puma"
# end
#
