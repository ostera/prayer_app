source 'http://rubygems.org'

gem 'rails', '3.2.11'
# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'
gem 'execjs'
gem 'therubyracer'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.0'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :development do
	#gem 'sqlite3'
	gem "pg"
	gem 'rspec-rails'
	gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
end

group :test do
  # Pretty printed test output
  #gem 'turn', '0.8.2', :require => false
	#gem 'sqlite3'
	gem "pg"
	gem 'rspec'
	gem 'webrat'
end

group :production do
  # gems specifically for Heroku go here
  gem "pg"
end
