source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.3.6'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
# A ruby implementation of the RFC 7519 OAuth JSON Web Token (JWT) standard.
gem 'jwt', '~> 1.5.6'
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
# Allows you to generate your JSON in an object-oriented and convention-driven manner.
gem 'active_model_serializers', '~> 0.10.0'
# Pagination library for Rails, Sinatra, Merb, DataMapper, and more
gem 'will_paginate', '~> 3.1.0'
# A port of Perl's Data::Faker library that generates fake data.
gem 'faker'

group :development, :test do
  # Brings the RSpec testing framework
  gem 'rspec-rails', '~> 3.5'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :test do
  # Provides Rails integration for factory_bot.
  gem 'factory_bot_rails', '~> 4.0'
  # RSpec- and Minitest-compatible one-liners that test common Rails functionality.
  gem 'shoulda-matchers', '~> 3.1'
    # A set of strategies for cleaning your database in Ruby.
  gem 'database_cleaner'
end

group :development do
  # Listens to file modifications and notifies you about the changes.
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # Makes Spring watch the filesystem for changes using Listen rather than by polling the filesystem.
  gem 'spring-watcher-listen', '~> 2.0.0'
end
