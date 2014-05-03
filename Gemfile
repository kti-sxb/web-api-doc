source 'https://rubygems.org'
gem 'rails', '4.1.0'
gem 'rails-i18n', '~> 4.0.0'
gem 'mysql2'
gem 'kaminari'
gem 'devise'

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

gem 'uglifier', '>= 1.3.0'
gem 'therubyracer',  platforms: :ruby
gem 'jquery-rails'

# Use unicorn as the app server
gem 'unicorn'

group :doc do
  gem 'sdoc', require: false
end

group :development, :test, :ci, :staging do
  gem 'zeus', '0.13.4.pre2'
  gem 'rspec-rails'
  gem 'factory_girl_rails', '~>1.4.0'
  gem 'simplecov', require: false
  gem 'simplecov-rcov'
end

group :development do
  gem 'capistrano',  '~> 3.1'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano3-unicorn'
end
