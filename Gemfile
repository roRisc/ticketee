source 'https://rubygems.org'

gem 'rails', '3.2.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

gem 'execjs'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :test, :development do 
  gem 'rspec-rails', '~> 2.5'
  gem "factory_girl", '~> 4.0' 
end

group :development do
  # To use debugger
  gem 'linecache19', '0.5.13', :path => '~/.rvm/gems/ruby-1.9.3-p194/gems/linecache19-0.5.13/'
  gem 'ruby-debug-base19x', '0.11.30.pre10', :path => '~/.rvm/gems/ruby-1.9.3-p194/gems/ruby-debug-base19x-0.11.30.pre10/'
  gem 'ruby-debug19', :require => 'ruby-debug'
end

group :test do
  gem 'cucumber-rails'
  gem 'capybara'
  gem 'database_cleaner'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

group :production do
  gem 'therubyracer'
end

