source 'https://rubygems.org'
ruby '2.3.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.15'
# Use SCSS for stylesheets
# gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
# gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'

#Heroku deployment
gem 'rails_12factor', group: :production

#Puma as webserver
gem 'puma'

group :development, :test do
  gem 'pry'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # https://github.com/bkeepers/dotenv
  gem 'dotenv-rails'
  gem 'minitest-rails-capybara'
  gem 'minitest-reporters'
  gem 'minitest-ci', :git => 'https://github.com/circleci/minitest-ci.git'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'

  # Spring speeds up development by keeping your application running in the background.
  # Read more: https://github.com/rails/spring
  # gem 'spring'

  gem 'guard'
  gem 'guard-minitest'

  gem 'terminal-notifier-guard'
end
