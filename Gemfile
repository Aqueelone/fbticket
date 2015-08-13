source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'

gem 'rake'

#auth
gem 'devise'
gem 'oauth2'
gem 'omniauth'
gem 'omniauth-facebook'

gem 'protected_attributes'
# Use postgresql9.4 as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'eventmachine'
gem 'em-synchrony'
gem 'em-websocket'
gem 'em-http-request'

# Use Capistrano for deployment
gem 'capistrano-rails', group: :development
gem 'active_record-annotate', group: :development

gem 'actionmailer'
gem 'whenever'
gem 'tinymce-rails'

gem 'therubyracer'
gem 'less-rails'
gem "twitter-bootstrap-rails"
gem 'compass'

gem 'turbolinks'
gem 'jquery-turbolinks'

# Localization
gem "http_accept_language"
gem "i18n-inflector-rails"
gem "rails-i18n"

# Mail
gem "markerb"
gem "messagebus_ruby_api"

group :production do # we don"t install these on travis to speed up test runs
  # Administration
  gem "rails_admin", "0.6.7"

  # Analytics
  gem "rack-google-analytics"
  gem "rack-piwik", require: "rack/piwik"

  # Click-jacking protection
  gem "rack-protection"

  # Process management
  gem "eye"

  # Redirects
  gem "rack-rewrite", require: true
  gem "rack-ssl", require: "rack/ssl"

  # Third party asset hosting
  gem "asset_sync", require: true
end

group :development do
  # Automatic test runs
  gem "guard-cucumber"
  gem "guard-jshintrb"
  gem "guard-rspec"
  gem "guard-rubocop"
  gem "guard", require: true
  gem "rb-fsevent", require: true
  gem "rb-inotify", require: true

  # Linters
  gem "jshintrb"
  gem "rubocop"

  # Preloading environment
  gem "spring"
  gem "spring-commands-rspec"
  gem "spring-commands-cucumber"
end

group :test do
  # RSpec (unit tests, some integration tests)
  gem "fixture_builder"
  gem "fuubar"
  gem "rspec-instafail", require: false
  gem "test_after_commit"

  # Cucumber (integration tests)
  gem "capybara"
  gem "database_cleaner"
  gem "selenium-webdriver"

  source "https://rails-assets.org" do
    gem "rails-assets-jquery-simulate"
    gem "rails-assets-jquery-simulate-ext"
  end

  # General helpers
  gem "factory_girl_rails"
  gem "timecop"
  gem "webmock", require: false
  gem "shoulda-matchers", require: false
end

group :development, :test do
  # RSpec (unit tests, some integration tests)
  gem "rspec-rails"

  # Cucumber (integration tests)
  gem "cucumber-rails", require: false

  # Jasmine (client side application tests (JS))
  gem "jasmine"
  gem "jasmine-jquery-rails"
  gem "rails-assets-jasmine-ajax", source: "https://rails-assets.org"
  gem "sinon-rails"

  # silence assets
  gem "quiet_assets"
  
  # local env up
  gem 'dotenv-rails'
end

