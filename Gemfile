# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'importmap-rails', '~> 1.0.1'
gem 'jbuilder', '~> 2.11.5'
gem 'pg', '~> 1.2.3'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.0'
gem 'redis', '~> 4.0'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

gem 'bootsnap', require: false
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'annotate', '~> 2.6.5'
  gem 'bullet', '~> 7.0'
  gem 'rubocop', '~> 1.24'
  gem 'rubocop-rails', '~> 2.13'
  gem 'rubocop-rspec', '~> 2.6'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'rspec', '~> 3.10'
  gem 'rspec-rails', '~> 5.0.2'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
