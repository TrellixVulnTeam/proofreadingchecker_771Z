source 'http://rubygems.org'

gem 'rails', '~> 3.2.13'
gem 'rack', '~> 1.4.5'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

group :production do
  gem 'mysql2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
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

# To use debugger
# gem 'debugger'

# This version needs to be hardcoded for OpenShift compatibility
gem 'thor', '= 0.14.6'

# This needs to be installed so we can run Rails console on OpenShift directly
gem 'minitest'

gem 'therubyracer'

group :development, :test do
     gem "rspec"
     gem "rspec-rails"
end

gem 'nokogiri'
gem 'faraday'