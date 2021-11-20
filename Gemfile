# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# ruby "3.0.0"
ruby RUBY_VERSION.to_s

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
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
# gem "redis", "~> 4.0"
# Use Active Model has_secure_password
# gem "bcrypt", "~> 3.1.7"

# Use Active Storage variant
# gem "image_processing", "~> 1.2"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.4", require: false
# Use postgres as database for Active Record
gem "pg"
# Support for i18n in javascript files
gem "i18n-js"

group :development, :test do
  # Automatically writes annotations about the database structure into model files
  gem "annotate"
  # Contracts let you clearly – even beautifully – express how your code behaves,
  # and free you from writing tons of boilerplate, defensive code.
  gem "contracts"
  # meta_request enables the Rails Panel in the Chrome browser - very helpful to debug
  gem "meta_request"
  # Debugger
  gem "pry"
  # Code coverage for Ruby
  gem "simplecov"
  gem "simplecov-lcov"
  # Standard - Ruby style guide, linter, and formatter
  gem "standard"
  # Like RuboCop but for code coverage. Inspects files in a git diff and warns on changed methods,
  # classes and blocks which need to be tested.
  gem "undercover"
  # Provides a dev bar and an overlay in-browser to visualize your UI's rendered partials
  gem "xray-rails"
end

group :development do
  # Awesome Print is a Ruby library that pretty prints Ruby objects in full color exposing their
  # internal structure with proper indentation. Rails ActiveRecord objects and usage within Rails
  # templates are supported via included mixins.
  gem "awesome_print"
  # Better Errors replaces the standard Rails error page with a much better and more useful error page. It is also usable outside of Rails in any Rack app as Rack middleware.
  gem "better_errors"
  # Needed for advanced features of better_errors
  gem "binding_of_caller"
  # Detect vulnerabilities in the code
  gem "brakeman", require: false
  # Patch-level verification for bundler.
  gem "bundler-audit"
  # Make your Rubies go faster with this command line tool highly inspired by fast-ruby and Sferik"s talk at Baruco Conf.
  gem "fasterer"
  # i18n-tasks helps you find and manage missing and unused translations.
  gem "i18n-tasks"
  # The listen gem listens to file modifications and notifies you about the changes.
  gem "listen", "~> 3.3"
  # overcommit is a tool to manage and configure Git hooks.
  gem "overcommit"
  # Pronto - another code quality checker
  gem "pronto"
  gem "pronto-rubocop", require: false
  gem "pronto-flay", require: false
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem "rack-mini-profiler", "~> 2.0"
  # Detecting where best practices are not followed
  gem "rails_best_practices"
  # Automatically generate an entity-relationship diagram (ERD) for your Rails models.
  gem "rails-erd"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  # Utility to format strings as a title (caps on all words)
  gem "titleize"
  # Web Console is a debugging tool for your Ruby on Rails applications.
  # Call console in your controllers or views gives you an interactive console in that context
  gem "web-console", ">= 4.1.0"
  # Check formatting and quality of yaml files
  gem "yamllint"
  # YARD is a documentation generation tool for the Ruby programming language.
  # It enables the user to generate consistent, usable documentation that can be exported to a
  # number of formats very easily, and also supports extending for custom Ruby constructs
  # such as custom class level definitions.
  gem "yard"
  # yard-contracts is a YARD plugin that works with the fantastic Contracts gem to automatically document
  # types and descriptions of parameters in your method signatures, saving time, making your code concise
  # and keeping your documentation consistent.
  gem "yard-contracts"
  # Yard-Junk: get rid of junk in your YARD docs!
  gem "yard-junk"
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem "capybara", ">= 3.26"
  # Dead-simple way to make Capybara and Selenium play together
  gem "capybara-selenium"
  # Used to clean the database between tests
  gem "database_cleaner"
  # Factories in testing
  gem "factory_bot_rails"
  # Use Rspec for automated tests
  gem "rspec"
  # rspec-rails brings the RSpec testing framework to Ruby on Rails as a drop-in alternative to its default testing framework, Minitest.
  gem "rspec-rails"
  # Commented, as I think this is included/superseded by the webdrivers gem
  # gem "selenium-webdriver"
  # rspec-tracer skips tests that are not needed looking at dependencies
  gem "rspec-tracer", require: false
  # Page object library
  gem "site_prism"
  # Easy installation and use of web drivers to run system tests with browsers
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
