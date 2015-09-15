source 'https://rubygems.org'

# ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

gem 'redcarpet'

gem 'capybara'
gem 'humanize'

gem 'figaro'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'twitter-bootstrap-rails'
gem 'less-rails'

gem 'faker'

gem 'rspec-rails'
# gem 'bootstrap-sass'
# gem 'autoprefixer-rails'

gem 'font-awesome-sass'

gem 'draper'

gem 'momentjs-rails'

gem 'omniauth-facebook'
gem "omniauth-google-oauth2"

gem 'bootstrap3-datetimepicker-rails'

gem 'pry-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :production do
  gem 'pg'
  gem 'rails_12factor', '0.0.2'
  gem "unicorn-rails"
end

group :development, :test do
  gem 'selenium-webdriver'
  gem 'database_cleaner'

  gem 'guard'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
# Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  gem 'guard-rails', require: false

  gem 'letter_opener'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  gem "bullet"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
