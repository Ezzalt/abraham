# frozen_string_literal: true
source 'http://rubygems.org'
ruby '3.3.4'

group :development, :test do
  gem 'sassc-rails'
end

gem "rails", '7.2.0.beta3'

# Declare your gem's dependencies in abraham.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
# gem 'byebug', group: [:development, :test]

group :development, :test do
  gem 'turbolinks'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'mocha'
end
