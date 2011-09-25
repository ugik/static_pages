source 'http://rubygems.org'

gem 'rails', '3.1.0'

gem 'sqlite3'

group :production do
  # gems specifically for Heroku go here
  gem 'pg'
  gem 'therubyracer-heroku'
end

group :development do
  gem 'rspec-rails', '2.6.1'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

